project(hello)

enable_testing()

add_executable(hello hello.cpp)


add_test(runhello hello)
