---
title: The Fixlet Debugger
---

The Fixlet Debugger is a graphical-based Client Relevance and Action Script languages tool that helps you to test and debug your Client 
Relevance statements and Action scripts on the system where the tool runs. 
Use it to fine-tune your Relevance Expressions and Action Scripts before deploying them to your production environment.

The Fixlet Debugger is available only on Windows platforms. 

The tool is installed automatically with the BigFix Console and, during the installation, a shortcut is automatically added in the Windows start menu.
You can also download a [stand-alone version](http://support.bigfix.com/bes/release/ ) of the Fixlet Debugger. 

**Note:** Ensure that both the Fixlet Debugger and the BigFix Client installed on the same system have the same version.

Double click the **FixletDebugger.exe** file to open the Fixlet Debugger user interface:

![Fixlet Debugger](/static/img/fixlet_debugger.png)

The tool includes four tabs:
<dl>
   <dt>*qna*</dt>
   <dd>Where you can enter your queries, preceded by **Q:**, and evaluate them all again whenever you click the **Evaluate** button.</dd>
   <dt>*single clause*</dt>
   <dd>Where you can enter and evaluate one query at a time. There is no need, in this case, to write **Q:**. Obtain detailed error information</dd>
   <dt>*graphical*</dt>
   <dd>Where the result of your query is split to display the evaluation of each single inspector involved in the query.</dd>
   <dt>*action*</dt>
   <dd>Where you can test your action script on the local system.</dd>
   </dl>
   
If the expression evaluates successfully, an answer to your query is displayed as an **A:** followed by the result of the expression. 

If an error occurs when evaluating the expression, or if the result does not exist on the current system, the result is an **E:** 
followed by the appropriate error message. All other lines are passed through unchanged. 

You can also obtain the number of microseconds it takes to calculate each relevance expression (T:). 
Each time that you press the Evaluate button, all existing lines that begin with A:, E:, or T: are removed before processing the next query.

For more information about this tool, view the following [video](https://www.youtube.com/watch?v=sujEc4HqXew).
