set_swift_llvm_is_available()
add_swift_host_library(swiftSyntaxParse STATIC
  SyntaxTreeCreator.cpp)
target_link_libraries(swiftSyntaxParse PRIVATE
  swiftParse
  swiftSyntax)
