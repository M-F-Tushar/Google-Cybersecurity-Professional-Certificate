# 🖥️ Inside the Operating System 🚀

## Understanding OS Operations 🌐

Previously, you learned about what operating systems are. Now, let's discuss how they work. In this note, we'll explore what happens with an OS when someone uses a computer for a task. Just like a car can't work without its engine, a computer can't work without its operating system. The job of an OS is to help other computer programs run efficiently by taking care of all the messy details related to controlling the computer's hardware. 🛠️

### Booting the Computer 💻

When you press the power button, you're interacting with the hardware. This boots the computer and brings up the operating system. Booting the computer means that a special microchip called a BIOS is activated. On many computers built after 2007, the chip was replaced by the UEFI. Both BIOS and UEFI contain booting instructions responsible for loading a special program called the bootloader, which then starts the operating system. Just like that, your computer is on! ⚡

### Vulnerabilities 📉

As a security analyst, understanding these processes can be helpful. Vulnerabilities can occur in something like a booting process. Often, the BIOS is not scanned by the antivirus software, making it vulnerable to malware infection. 🦠

### Communicating with the System 🗣️

The process starts with you, the user. To complete tasks, you use applications on your computer. An application is a program that performs a specific task. When you do this, the application sends your request to the operating system, which then interprets this request and directs it to the appropriate component of the computer's hardware. Hardware consists of all the physical components of the computer. The hardware also sends information back to the operating system, which in turn is sent back to the application. 🔄

### Example: Using the Calculator 📱

Let's give a simple overview of how this works when you want to use the calculator on your computer. You use your mouse to click on the calculator application on your computer. When you type in the number you want to calculate, the application communicates with the operating system. Your operating system then sends a calculation to a component of the hardware, the central processing unit (CPU). Once the hardware does the work of determining the final number, it sends the answer back to your operating system, which then displays it in your calculator application. 🧮

### Importance for Security Analysts 🛡️

Understanding this process is helpful when investigating security events. Security analysts should be able to trace back through this process flow to analyze where a security event could have occurred. Just like a mechanic needs to understand the inner workings of a car more than an average driver, recognizing how operating systems work is important knowledge for a security analyst. 🔍

