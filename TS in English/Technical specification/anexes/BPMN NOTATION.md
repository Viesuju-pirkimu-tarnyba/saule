## BPMN NOTATION

The figure below shows the simplified BPMN notation values, and the table contains the notation explanations.

![image](https://user-images.githubusercontent.com/61745726/92333849-5c702900-f091-11ea-94f3-913b69bcf6f9.png)

Fig. 9.1. Simplified BPM notation explanation 

Table 1. BPM notation description

<table width="100%">
<thead>
<tr>
<td width="33%">
<p>Notation</p>
</td>
<td width="66%">
<p>Explanation</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td colspan="2" width="100%">
<p>Pools and lanes</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Pool</p>
</td>
<td width="66%">
<p>Pool, which shows the process steps performed by a particular process participant or the environment in which these process steps are performed, such as an information system.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Lane</p>
</td>
<td width="66%">
<p>The pool is divided into lanes, which show the process steps performed by specific participants in a specific environment, such as a specific information system environment - the divided lanes denote the participants who perform the process steps in the lanes.</p>
</td>
</tr>
</tbody>
<thead>
<tr>
<td colspan="2" width="100%">
<p>Solutions and conditions</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>Solution or merging;</p>
<p>Solution or merging (completed)</p>
</td>
<td width="66%">
<p>Solution, condition or linking after a decision condition. The process is continued by only one branch whose condition is met.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Parallel separation or merging</p>
</td>
<td width="66%">
<p>Separating or merging of steps in parallel. All output sequences start running in parallel until they end or merge. When merging sequences, it is waited for all merging sequences to reach the merging.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Solution or merging (or)</p>
</td>
<td width="66%">
<p>Solution, condition or linking after a solution condition. There may be more than one suitable condition.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Event-based solution or merging</p>
</td>
<td width="66%">
<p>Event-based condition. It checks whether the intended event has occurred and when it occurs, the process follows the intended sequence.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Complex solution or merging</p>
</td>
<td width="66%">
<p>Solution, condition or linking after a decision condition. There may be more than one suitable condition. Usually used when there are 4 or more conditions.</p>
</td>
</tr>
</tbody>
<thead>
<tr>
<td colspan="2" width="100%">
<p>Flow</p>
</td>
</tr>
<tr>
<td colspan="2" width="100%">
<p>Reference to next steps</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>Reference to the next step</p>
</td>
<td width="66%">
<p>Reference to the next step in the same process</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Conditional reference to the next step</p>
</td>
<td width="66%">
<p>Reference to the next step in the same process if the specified condition is met. Can be used in place of a solution or condition.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Reference to the next step by default</p>
</td>
<td width="66%">
<p>Reference to the next step in the same process used in the decision element to indicate the branch in which the process takes place without satisfying all other conditions.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Message flows</p>
</td>
<td width="66%">
<p>Information flow, for example, by sending a message between participants.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Association</p>
</td>
<td width="66%">
<p>Attaching artifacts (such as data objects) to process steps.</p>
</td>
</tr>
</tbody>
<thead>
<tr>
<td colspan="2" width="100%">
<p>Events</p>
</td>
</tr>
<tr>
<td colspan="2" width="100%">
<p>Starting events</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>Simple</p>
</td>
<td width="66%">
<p>Process beginning.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Timer</p>
</td>
<td width="66%">
<p>Process beginning, informing that the process starts at a certain time or time interval.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Message</p>
</td>
<td width="66%">
<p>Process beginning, informing you that a message has been received.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Signal</p>
</td>
<td width="66%">
<p>Process beginning, informing you that a signal has been received.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Conditional</p>
</td>
<td width="66%">
<p>Process beginning, if the specified condition is met.</p>
</td>
</tr>
</tbody>
<thead>
<tr>
<td colspan="2" width="100%">
<p>Intermediate events</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>Message</p>
</td>
<td width="66%">
<p>An intermediate event in a process that indicates that a sent or received message has been received.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Timer</p>
</td>
<td width="66%">
<p>An intermediate event in a process that indicates that it is resuming at a specific time or after a time interval.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Relation</p>
</td>
<td width="66%">
<p>The element that links the process references to the next step. One outbound event is merged with one inbound event by assigning them the same identifier.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Error</p>
</td>
<td width="66%">
<p>An intermediate event in the process indicating that an error has occurred.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Signal</p>
</td>
<td width="66%">
<p>An intermediate event in a process of sending and receiving a signal.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Condition</p>
</td>
<td width="66%">
<p>An intermediate event in a process under a certain condition.</p>
</td>
</tr>
</tbody>
<thead>
<tr>
<td colspan="2" width="100%">
<p>End events</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>Simple</p>
</td>
<td width="66%">
<p>End of the branch of the process.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Message</p>
</td>
<td width="66%">
<p>End of the process branch by sending a message.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Termination</p>
</td>
<td width="66%">
<p>Process end immediately completing the entire process.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Signal</p>
</td>
<td width="66%">
<p>End of the process branch by sending a signal.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Error</p>
</td>
<td width="66%">
<p>End of the process branch indicating that an error has occurred.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Stop</p>
</td>
<td width="66%">
<p>End of the branch of the proceedings indicating that the execution of the branch is terminated due to certain circumstances.</p>
</td>
</tr>
</tbody>
<thead>
<tr>
<td colspan="2" width="100%">
<p>Activities</p>
</td>
</tr>
<tr>
<td colspan="2" width="100%">
<p>Process steps</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>Process step</p>
</td>
<td width="66%">
<p>A process step which activities are not shared.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>User process step</p>
</td>
<td width="66%">
<p>A process step which activities are not shared when it is desired to emphasize that the step is performed by the user.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>A step in the multi-instance process</p>
</td>
<td width="66%">
<p>Process step, indicating that the activity in the process step can be performed multiple times as long as necessary.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Sending process step</p>
</td>
<td width="66%">
<p>A process step that can send a message, error, signal and etc. After sending, the process proceeds to the next step.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Receiving process step</p>
</td>
<td width="66%">
<p>A process step that can receive a message, error, signal and etc. After receipt, the process step runs and proceeds to the next step.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Cycle</p>
</td>
<td width="66%">
<p>A process step that can be performed multiple times, specifying the number of times or another condition.</p>
</td>
</tr>
</tbody>
<thead>
<tr>
<td colspan="2" width="100%">
<p>Sub-processes</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>Reduced Sub-process</p>
</td>
<td width="66%">
<p>Sub-process step. A complex process, which activities are invisible.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Extended Sub-process</p>
</td>
<td width="66%">
<p>Sub-process step. A composite process, which activities are visible (it depicts a process).</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Calling Sub-process step</p>
</td>
<td width="66%">
<p>Sub-process step. Indicates that the Sub-process is called, which is shown in the next diagram</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Cycle</p>
</td>
<td width="66%">
<p>A Sub-process step that can be performed multiple times, specifying the number of times or another condition.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>A step in the multi-instance Sub-process</p>
</td>
<td width="66%">
<p>Sub-process, indicating that the activity in the process step can be performed multiple times as long as necessary.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Ad-hoc Sub-process step</p>
</td>
<td width="66%">
<p>A Sub-process in which the order in which the steps of the process are described is not relevant.</p>
</td>
</tr>
</tbody>
<thead>
<tr>
<td colspan="2" width="100%">
<p>Artifacts</p>
</td>
</tr>
</thead>
<tbody>
<tr>
<td width="33%">
<p>Data object</p>
</td>
<td width="66%">
<p>Data generated during the process or data that is used by the running process.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Data storage</p>
</td>
<td width="66%">
<p>Data storage is where a process can write or read data, and which exists outside the process.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Group</p>
</td>
<td width="66%">
<p>An informal way to group chart elements, such as highlighting an area that requires additional analysis.</p>
</td>
</tr>
<tr>
<td width="33%">
<p>Comment</p>
</td>
<td width="66%">
<p>A text comment, explanation, or other description helping to understand the process.</p>
</td>
</tr>
</tbody>
</table>
