# How to add a CheckBox into the Node Indicator Cells


<p>This example demonstrates how to display a check box within the Node Indicator Cells, and control node values by clicking it. To accomplish this task, do the following:<br />
1. Handle the TreeList's <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraTreeListTreeList_CustomDrawNodeIndicatortopic"><u>CustomDrawNodeIndicator</u></a> event and paint check boxes manually. <br />
2. Handle the TreeList's MouseDown event, calculate the <a href="http://documentation.devexpress.com/#WindowsForms/clsDevExpressXtraTreeListTreeListHitInfotopic"><u>HitInfo </u></a>object using the TreeList's <a href="http://documentation.devexpress.com/#WindowsForms/DevExpressXtraTreeListTreeList_CalcHitInfotopic"><u>CalcHitInfo </u></a>method to determine the area that has been clicked.</p>

<br/>


