# Build

## Bazel

### Hello
* Hello World와 같이 기본적인 테스트를 위한 코드  
> bazel build //:hello  
> bazel run //:hello  

## CMake

### Hello
* Hello World와 같이 기본적인 테스트를 위한 코드
> cd /your/workspace/edugit  
> cmake -Bbuild -H.  
> cmake --build build  
> cmake --build build --target run_hello  
