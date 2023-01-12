If you find a bug in {$product.name$} please report it with a [GitHub Issue](https://github.com/HCL-TECH-SOFTWARE/rtist-in-code/issues). Please include steps to reproduce and any additional files that can help in troubleshooting. For example, it can be good to include all log files. You can find the location of these logs by invoking the command `Developer: Open Logs Folder`. You can zip the entire logs folder and attach it to the issue. You can also check these logs using the Output view. In particular, the following two output logs are relevant:

* **Art Server** Contains messages printed by the Art language server. These are internal errors and other diagnostic messages that you normally would not need to pay attention to, but which can sometimes be useful when troubleshooting a problem.
* **Art Build** Contains messages printed when building a TC. It can sometimes contain diagnostic messages from the Art compiler.