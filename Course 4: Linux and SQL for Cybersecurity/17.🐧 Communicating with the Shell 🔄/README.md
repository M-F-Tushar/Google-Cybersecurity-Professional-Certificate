# 🐧 Communicating with the Shell 🔄

## Introduction
Hello again! In this note, we're going to learn a little more about the shell and how to communicate with it. Communicating with a computer is like having a conversation with your friend. One person asks a question, and the other person answers with a response. If you don't know the answer, you can just say you don't know the answer. 🤷‍♂️

## Standard Input 📥
When you communicate with the shell, the commands in the shell can take input, give output, or give error messages. Standard input consists of information received by the OS via the command line. This is like you asking your friend a question during a conversation. The information is input from your keyboard to the shell. If the shell can interpret your request, it asks the kernel for the resources it needs to execute the related task. 🌟

## Standard Output 📤
Standard output is the information returned by the OS through the shell. In the same way that your friend gives an answer to your question, output is a computer's response to the command you input. Output is what you receive. Let's pick up where we left off in our example and send the input of: `echo hello` to the OS by pressing enter. Immediately, the shell returns the output of: `hello`. 👋

## Standard Error ❌
Standard error contains error messages returned by the OS through the shell. Just like your friend might indicate that they can't answer a question, the system responds with an error message if they can't respond to your command. Sometimes this might occur when we misspell a command or the system doesn't know the response to the command. Other times, it might happen because we don't have the appropriate permissions to perform a command. We'll explore another example that demonstrates standard error. Let's input: `eco hello` into the shell. Notice I intentionally misspelled echo as `e-c-o`. When we press enter, an error message appears. 🚫

## Conclusion 🌟
To wrap up, we've covered the basics of communication with the shell. Communication with the shell can only go in one of three ways: the system receives a command—this is input; the system responds to the command and produces output; and finally, the system doesn't know how to respond, resulting in an error. Later, you'll become much more familiar with this as we explore commands useful for security professionals. 🔍

