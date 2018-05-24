# Splunk.Client
C# libraries needed to access your Splunk instance

The versions currently under Nuget do not work as it gets this error:

<b>Description: An assembly (probably "Splunk.Client") must be rewritten using the code contracts binary rewriter (CCRewrite) because it is calling Contract.Requires and the CONTRACTS_FULL symbol is defined. Remove any explicit definitions of the CONTRACTS_FULL symbol from your project and rebuild. CCRewrite can be downloaded from http://go.microsoft.com/fwlink/?LinkID=169180. After the rewriter is installed, it can be enabled in Visual Studio from the project's Properties page on the Code Contracts pane. Ensure that "Perform Runtime Contract Checking" is enabled, which will define CONTRACTS_FULL.</b>

Getting the source code and recompiling this will work, but if that is too much work, just use the libraries here and you will be good to go.

