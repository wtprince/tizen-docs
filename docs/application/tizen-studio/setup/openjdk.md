<<<<<<< HEAD
# OpenJDK 12 and OpenJFX Installation Guide
=======
# OpenJDK 10 and OpenJFX Installation Guide
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5

Open Java Development Kit (OpenJDK) is an open source implementation of the Java Standard Edition (Java SE) platform with contribution from Oracle and the open Java community. For more information, see [OpenJDK](http://openjdk.java.net/).

Open JavaFX (OpenJFX) is an open source, next generation client application platform for desktop, mobile and embedded systems built on Java. For more information, see [JavaFX](https://openjfx.io/).

Before JDK version 9, JavaFX libraries were included in the JDK distribution. Since JDK version 9, JavaFX (JFX) is provided as a separate package.

<<<<<<< HEAD
This document explains how to install the OpenJDK version 12 along with OpenJFX libraries for the following operating systems:
=======
This document explains how to install the OpenJDK version 10 along with OpenJFX libraries for the following operating systems:
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5

- [Windows](#install-openjdk-for-windows)
- [Linux](#install-openjdk-for-ubuntu)
- [MacOS](#install-openjdk-for-macos)

## Install OpenJDK

To install OpenJDK, you must download it as follow:
<<<<<<< HEAD
1. Download the OpenJDK version 12 from [https://jdk.java.net/archive/](https://jdk.java.net/archive/).

2. Extract the .tar file. The `jdk-12.0.2` folder appears.

### Install OpenJDK for Windows

This section explains how to install the OpenJDK version 12 for Windows:
=======
1. Download the OpenJDK version 10 from [https://jdk.java.net/10/](https://jdk.java.net/10/).

2. Extract the .tar file. The `jdk-10.0.2` folder appears.

### Install OpenJDK for Windows

This section explains how to install the OpenJDK version 10 for Windows:
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5

1. Go to **Start** > **Control Panel** > **System and Security** > **System**.

2. Click **Advanced system settings**. The **System Properties** window appears.

3. Click **Environment Variables...**. The **Environment Variables** window appears.

4. Click **New...** in the **User variables for \<user name\>** section.
    > **Note**
    >
    > If your `JAVA_HOME` variable is already created, select it and click **Edit...**.

<<<<<<< HEAD
5. Enter `JAVA_HOME` in the variable name field and the JDK directory path, for example, `C:\Users\user\Desktop\jdk-12.0.2`, in the Variable value field.
=======
5. Enter `JAVA_HOME` in the variable name field and the JDK directory path, for example, `C:\Users\user\Desktop\jdk-10.0.2`, in the Variable value field.
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5

6. Click **OK**. The Environment Variables window appears.

7. If you cannot find `JAVA_HOME` in **System variables** section, add the variable by repeating the 4, 5, and 6 steps.

<<<<<<< HEAD
12. Save and close the **Environment Variables** window.

11. Launch **Command Prompt**.

12. Run the following command to verify whether the OpenJDK version 12 is installed:
=======
10. Save and close the **Environment Variables** window.

11. Launch **Command Prompt**.

12. Run the following command to verify whether the OpenJDK version 10 is installed:
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
    ```
    java -version
    ```

### Install OpenJDK for Ubuntu

<<<<<<< HEAD
This section explains how to install the OpenJDK version 12 for Ubuntu:
=======
This section explains how to install the OpenJDK version 10 for Ubuntu:
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5

1. Launch the **Terminal** application.

2. Run the following command in the terminal to set the `JAVA_HOME` as OpenJDK directory path, for example:
    ```
<<<<<<< HEAD
    JAVA_HOME=/home/<username>/Desktop/openJDK/jdk-12.0.2/
=======
    JAVA_HOME=/home/<username>/Desktop/openJDK/jdk-10.0.2/
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
    ```

3. Run the following commands in the terminal:
    ```
    sudo update-alternatives --install /usr/bin/java java ${JAVA_HOME}/bin/java 20000
    sudo update-alternatives --install /usr/bin/javac javac ${JAVA_HOME}/bin/javac 20000
    ```

4. Run the following command to get a list of JDK versions installed:
    ```
    sudo update-alternatives --config java
    ```
    > **Note**
    >
    > If there are multiple JDK installed, select the required java version by entering the selection number.

5. Run the following command:
    ```
    sudo update-alternatives --config javac
    ```
    > **Note**
    >
    > `javac` is for compilation. For more information on differences between java and javac, see https://docs.oracle.com.

4. Select the required javac version as mentioned above.

<<<<<<< HEAD
6. Run the following command to verify whether the OpenJDK version 12 is installed:
=======
6. Run the following command to verify whether the OpenJDK version 10 is installed:
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
    ```
    java -version
    ```

### Install OpenJDK for MacOS

<<<<<<< HEAD
This section explains how to install the OpenJDK version 12 for macOS:
=======
This section explains how to install the OpenJDK version 10 for macOS:
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5

1. Copy the downloaded jdk folder to the `Library/Java/JavaVirtualMachines` location. This is the default location where all the JDKs are available. Use the following command to copy the JDK directory.
    ```
    cp -aR <downloaded_jdk_path> /Library/Java/JavaVirtualMachines/
    ```

2. Launch **Terminal** application.

<<<<<<< HEAD
3. Run the following command to verify whether the OpenJDK version 12 is installed:
=======
3. Run the following command to verify whether the OpenJDK version 10 is installed:
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5
    ```
    java -version
    ```

    > **Note**
    >
<<<<<<< HEAD
    > If the OpenJDK version 12 is not installed, add the `export JAVA_HOME = /Library/Java/JavaVirtualMachines/jdk-12.jdk/Contents/Home` command in the `.profile` or `.bash_profile` file.
=======
    > If the OpenJDK version 10 is not installed, add the `export JAVA_HOME = /Library/Java/JavaVirtualMachines/jdk-10.jdk/Contents/Home` command in the `.profile` or `.bash_profile` file.
>>>>>>> 9b69ef98c4468c79bcc386c40b15e9707d0c6ab5


## Install OpenJFX

After installing OpenJDK, install the OpenJFX:

1. Download the OpenJFX version 11 from [https://gluonhq.com/products/javafx](https://gluonhq.com/products/javafx/).
    > **Note**
    >
    > Download the appropriate JavaFX product for your operating system.

2. Extract the downloaded zip file.

3. Copy all files in `lib` folder to `lib` folder of `JAVA_HOME`.
   > **Note**
   >
   > On Ubuntu, run the following command:
   > ```
   > cd javafx-sdk-11.0.1
   > sudo cp -arf lib/* ${JAVA_HOME}/lib/
   > ```

4. Copy all files in `bin` folder to `bin` folder of `JAVA_HOME`.
   > **Note**
   >
   > This step is only required for Windows.

