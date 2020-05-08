# Raspberry-Pi Bare Metal Tutorial

이 저장소에는 C로 작성된 Raspberry Pi Bare Metal 프로그래밍 코드가 포함되어 있습니다. 튜토리얼의 내용과 코드에 관련된 모든 글은 [valvers.com](https://www.valvers.com/open-software/raspberry-pi/bare-metal-programming-in-c) 및 [github](https://github.com/BrianSidebotham/arm-tutorial-rpi)에 있습니다.

Linux에서 빌드 할 수 있습니다 - 개발하려는 경우 Windows에서 VM으로 Linux를 사용하거나 데스크톱에 Linux를 설치하여 사용할 수 있습니다.

> **NOTE**: 이 튜토리얼은 Windows에서 테스트를 했지만 Windows에서 모든 것을 테스트할 수 있는 시간이 없어 제외되었습니다.

## 시작하기

이 저장소를 클론하고 툴체인과 펌웨어를 얻습니다.

튜토리얼에 사용된 툴체인은 컴파일러를 다운로드하는 `compiler/get_compiler.sh` 스크립트로 가져올 수 있으므로 Linux 배포판에서 특정 패키지를 설치할 필요가 없습니다.

마찬가지로, Raspberry Pi 펌웨어도 필요합니다. `firmware/get_firmware_repo.sh` 스크립트를 사용하여 가져올 수 있습니다.

튜토리얼을 읽어 재미있게 즐기고, 실험하는 것을 잊지 마세요!

## 튜토리얼 링크

[Step01 - Getting Started](/part-1/readme.md)

[Step02 - C Runtime](/part-2/readme.md)

[Step03 - Introducing CMake](/part-3/readme.md)

[Step04 - Interrupts](/part-4/readme.md)

[Step05 - Graphics(Basic)](/part-5/readme.md)

## 흥미로운 링크들

- [Cambridge Tutorial](http://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/os/index.html)

- [ARM Instruction Reference](http://infocenter.arm.com/help/topic/com.arm.doc.qrc0001l/QRC0001_UAL.pdf)

- [Circle C++ Bare Metal Environment for RPI](https://github.com/rsta2/circle)

- [Newlib C-Library documentation](https://sourceware.org/newlib/libc.html)
