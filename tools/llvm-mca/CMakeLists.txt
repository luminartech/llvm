set(LLVM_LINK_COMPONENTS
  AllTargetsAsmPrinters
  AllTargetsAsmParsers
  AllTargetsDescs
  AllTargetsDisassemblers
  AllTargetsInfos
  MC
  MCParser
  Support
  )

add_llvm_tool(llvm-mca
  Backend.cpp
  BackendPrinter.cpp
  CodeRegion.cpp
  DispatchStage.cpp
  DispatchStatistics.cpp
  FetchStage.cpp
  HWEventListener.cpp
  InstrBuilder.cpp
  Instruction.cpp
  InstructionInfoView.cpp
  InstructionTables.cpp
  LSUnit.cpp
  llvm-mca.cpp
  RegisterFile.cpp
  RegisterFileStatistics.cpp
  ResourcePressureView.cpp
  RetireControlUnit.cpp
  RetireControlUnitStatistics.cpp
  RetireStage.cpp
  Scheduler.cpp
  SchedulerStatistics.cpp
  Stage.cpp
  Support.cpp
  SummaryView.cpp
  TimelineView.cpp
  View.cpp
  )
