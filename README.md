<h1>Burp Suite: Repeater </h1>


<h2>Description</h2>
This lab is an introduction to the basics of Burp Suite Repeater. Burp Suite Repeater is a tool that allows users to capture, edit and resend HTTP requests to a target server. Repeater allows users to work on multiple messages simultaneously by allowing users to repeatedly send a request. By resending the same request with a different input each time, input-based vulnerabilities can be confirmed. 
<br />


<h2>Tools Used</h2>

- <b>Burp Suite Repeater</b>

<h2>Burp Suite Repeater Walkthrough:</h2>

<p align="center">
Send request to repeater by right-clicking: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Repeater/blob/main/Send%20to%20Repeater.png?raw=true" height="80%" width="80%" alt="Send to repeater"/>
<br />
<br />
Send a request to populate the Response view:  <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Repeater/blob/main/Send%20to%20repeater%202.png?raw=true"/><br />
<br />
<br />
After clicking send in Repeater, the Response view is populated and can be adjusted with 4 options. <br/>
<br />
1. Pretty<br />
2. Raw<br />
3. Hex<br />
4. Render<br />
<br />
We are able to edit the HTML header by changing values for ProductID: <br />
<img src="https://github.com/Kieyontay/Burp-Suite-Repeater/blob/main/Input%20change%201.png?raw=true" height="80%" width="80%" alt="Edit header"/> <br />
<br />
Resend the request with different input by changing the ProductID parameter: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Repeater/blob/main/Input%20change%202.png?raw=true" height="80%" width="80%" alt="ProductID Value Change"/> <br />
The updated page will show in the Response panel.
<br />
<br />
After clicking send, click the Render option in the Response panel to view the updated webpage: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Repeater/blob/main/Render%20response%20to%20changed%20input.png?raw=true" height="80%" width="80%" alt="Repeater Render Results"/> <br />
<br />
<br />
We are able to view the request history here: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Repeater/blob/main/Previous%20results.png?raw=true" height="80%" width="80%" alt="Request history"/> <br />
<br />
<br />
We can try to send unexpected results: <br/>
<img src="https://github.com/Kieyontay/Burp-Suite-Repeater/blob/main/Not%20found%20err%20message.png?raw=true" height="80%" width="80%" alt="Repeater unexpected results"/> <br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
