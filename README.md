## OpenICE-lite User App: Base repository

This repository is a skeleton to implement an user-application utilizing the [OpenICE-lite Core](https://github.com/samdware/openice-lite) and other provided modules.

### Requirements
In order to use OpenICE-lite, you need:
- Java 1.8 installed
- MQTT credential (if you plan to use MQTT middleware)

### Other examples
Our team also provides some executable-ready examples as listed below:
- [Dongle Simulator](https://github.com/samdware/openice-lite-example-dongle-simulator)
- [Masimo Rad-8 Dongle](https://github.com/samdware/openice-lite-example-masimo-rad8)

### Important files
1. `build.gradle`

	OpenICE-lite utilizes [Gradle](https://gradle.org/) as the build tool. The build configuration is specified in the `build.gradle` file, mainly dependencies, tasks. If you need to include additional OpenICE-lite modules, you can add them into this build file.

2. `src/main/java/App.java`

	This is where your main application is executed (with the current Gradle build).

### How to run
To run the application, execute the following command:
- On Unix system
```
./gradlew run
```
- On Windows system
```
gradlew.bat run
```

### DISCLAIMER
USE OF THIS SOFTWARE IN ANY WAY AND RELIANCE ON THE CONTENTS IS DONE AT THE USER'S DISCRETION AND RISK. YOU HEREBY AGREE THAT YOU WILL BE SOLELY RESPONSIBLE FOR ANY DAMAGE OR HARM THAT RESULTS FROM SUCH USE. THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.