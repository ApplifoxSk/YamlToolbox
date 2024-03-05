Several years ago during spring of 2020 I looked on internet sites for some free library or samples with implementation math processor. I found only some math implementations with basic operation without usage of variables.

Reason of math processor implementation request was pilot project of some industry application, which needed preprocessing of presets of variety variables of electrical quantities and postprocessing realted to combination of parameter presets and result of measured values.

So I decided to wrote quick simple prototype of expressions parser with expression formatting, which allows simple and quick parsing of expression "on the fly" during expression evaluation calls.

Code implementing expression parsing and evaluation of basic and some advanced math operations were operated several years in prototype mentioned above with it's operational reliability and code processing error and exception handling with fault tolerant error reporting directly to expression result.

If you belongs to group of engineers, scientinsts or students, who need to include simple math expressions evalation into your application, you can try to use **ExpressionProcessor** .NET library.

Processing of variables is implemented via simple class **TagsRepository** included in **RepositoryModel** .NET library.

**Variable tags are configured in simple text file formatted as YAML document.** YamlDotNet NuGet is used to manage deserialization of this yaml file.

Example of usage is presented in simple console .NET application.



