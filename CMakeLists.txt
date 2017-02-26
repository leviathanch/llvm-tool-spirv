set(LLVM_LINK_COMPONENTS
  Analysis
  BitReader
  BitWriter
  IPO
  SPIRVlibSPIRV
  SPIRVCodeGen
  Core
  Support
  TransformUtils
  )

add_llvm_tool(llvm-spirv
  llvm-spirv.cpp
  )
