<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>zap_report.md</title>
<link
	href="2025-03-15-ZAP-Report-2/normalize/normalize.css" rel="stylesheet">
<link
	href="2025-03-15-ZAP-Report-2/themes/original/main.css" rel="stylesheet">
<link
	href="2025-03-15-ZAP-Report-2/themes/original/colors.css" rel="stylesheet">
</head>
<body>
	<header>
		<h1>zap_report.md</h1>
		<p>
			<span>Generated with</span> <a href="https://zaproxy.org"><img
				src="2025-03-15-ZAP-Report-2/zap32x32.png" alt="The ZAP logo" class="zap-logo">ZAP</a>
			<span>on Sat 15 Mar 2025, at 09:18:25</span>
		</p>
		<p>ZAP Version: 2.16.0</p>
		<p>
			ZAP by <a href="https://checkmarx.com/">Checkmarx</a>
		</p>
	</header>

	<main>

		<section id="contents" class="contents">
			<h2>Contents</h2>
			<nav>
				<ol>
					<li><a
						href="#about-this-report">About this report</a>
						<ol>
							
							<li><a
								href="#report-parameters">Report parameters</a></li>
						</ol></li>
					<data-th-block>
					<li><a
						href="#summaries">Summaries</a>
						<ol>
							<li><a
								href="#risk-confidence-counts">Alert counts by risk and confidence</a></li>
							<li><a
								href="#site-risk-counts">Alert counts by site and risk</a></li>
							<li><a
								href="#alert-type-counts">Alert counts by alert type</a></li>
						</ol></li>
					<li><a
						href="#alerts">Alerts</a>
						<ol>
							
							 
							
							
							
							
							<li><a
								href="#alerts--risk-2-confidence-3"><span>Risk</span>=<span
									class="risk-level">Medium</span>, <span>Confidence</span>=<span
									class="confidence-level">High</span> <span>(1)</span></a></li>
							
							
							
							
							  
							 
							
							
							
							
							
							
							<li><a
								href="#alerts--risk-0-confidence-2"><span>Risk</span>=<span
									class="risk-level">Informational</span>, <span>Confidence</span>=<span
									class="confidence-level">Medium</span> <span>(2)</span></a></li>
							
							<li><a
								href="#alerts--risk-0-confidence-1"><span>Risk</span>=<span
									class="risk-level">Informational</span>, <span>Confidence</span>=<span
									class="confidence-level">Low</span> <span>(2)</span></a></li>
							  
						</ol></li>
					<li><a
						href="#appendix">Appendix</a>
						<ol>
							<li><a
								href="#alert-types">Alert types</a></li>
						</ol></li>
					</data-th-block>
				</ol>
			</nav>
		</section>

		<section
			id="about-this-report" class="about-this-report">
			<h2>About this report</h2>

			

			<section
				id="report-parameters">
				<h3>Report parameters</h3>
				<div class="report-parameters--container">
					<h4>Contexts</h4>
					
					
					<p>No contexts were selected, so all contexts were included by default.</p>
					  

					<h4>Sites</h4>
					
					<p>The following sites were included:</p>
					<ul class="sites-list">
						<li><span class="site">http://alibaba.zaproxy.org</span></li>
						<li><span class="site">http://100.100.100.200</span></li>
						<li><span class="site">http://metadata.oraclecloud.com</span></li>
						<li><span class="site">http://metadata.google.internal</span></li>
						<li><span class="site">http://aws.zaproxy.org</span></li>
						<li><span class="site">http://169.254.169.254</span></li>
						<li><span class="site">http://localhost:8080</span></li>
					</ul>
					
					<p>(If no sites were selected, all sites were included by default.)</p>
					<p>An included site must also be within one of the included contexts for its data to be included in the report.</p>

					<h4>Risk levels</h4>
					<p>
						<span>Included</span>:
						 
						<span class="included-risk-codes"><span class="risk-level">High</span>, <span class="risk-level">Medium</span>, <span class="risk-level">Low</span>, <span class="risk-level">Informational</span></span>
					</p>
					<p>
						<span>Excluded</span>:
						 <span>None</span>
						
					</p>

					<h4>Confidence levels</h4>
					<p>
						<span>Included</span>:
						
						
						<span class="included-confidence-codes"><span class="confidence-level">User Confirmed</span>, <span class="confidence-level">High</span>, <span class="confidence-level">Medium</span>, <span class="confidence-level">Low</span></span>
					</p>
					<p>
						<span>Excluded</span>:
						
						
						<span class="included-confidence-codes"> <span class="confidence-level">User Confirmed</span>, <span class="confidence-level">High</span>, <span class="confidence-level">Medium</span>, <span class="confidence-level">Low</span>, <span class="confidence-level">False Positive</span></span>
					</p>
				</div>
			</section>
		</section>

		
		<section>
			
		</section>
		
		<section id="summaries" class="summaries">
			<h2>Summaries</h2>

			<section
				id="risk-confidence-counts">
				<h3>Alert counts by risk and confidence</h3>
				<table class="risk-confidence-counts-table">
					<caption>
						<p>This table shows the number of alerts for each level of risk and confidence included in the report.</p>
						<p>(The percentages in brackets represent the count as a percentage of the total number of alerts included in the report, rounded to one decimal place.)</p>
					</caption>
					<colgroup>
						<col>
						<col>
					</colgroup>
					<colgroup>
						<col
							style="width: 14.0%"><col
							style="width: 14.0%"><col
							style="width: 14.0%"><col
							style="width: 14.0%">
						<col style="width: 14.0%">
					</colgroup>
					<thead>
						<tr>
							<td colspan="2" rowspan="2"></td>
							<th scope="colgroup"
								colspan="5">Confidence</th>
						</tr>
						<tr>
							<th scope="col">User Confirmed</th>
							<th scope="col">High</th>
							<th scope="col">Medium</th>
							<th scope="col">Low</th>
							<th scope="col">Total</th>
						</tr>
					</thead>
					<tbody>
						<tr>
							<th scope="rowgroup"
								rowspan="5">Risk</th>
							<th scope="row">High</th>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>0</span><br> <span class="additional-info-percentages">(0.0%)</span></td>
						</tr>
						<tr>
							
							<th scope="row">Medium</th>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>1</span><br> <span
								class="additional-info-percentages">(20.0%)</span></td>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>1</span><br> <span class="additional-info-percentages">(20.0%)</span></td>
						</tr>
						<tr>
							
							<th scope="row">Low</th>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>0</span><br> <span class="additional-info-percentages">(0.0%)</span></td>
						</tr>
						<tr>
							
							<th scope="row">Informational</th>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>2</span><br> <span
								class="additional-info-percentages">(40.0%)</span></td>
							<td><span>2</span><br> <span
								class="additional-info-percentages">(40.0%)</span></td>
							<td><span>4</span><br> <span class="additional-info-percentages">(80.0%)</span></td>
						</tr>
						<tr>
							<th scope="row">Total</th>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0.0%)</span></td>
							<td><span>1</span><br> <span
								class="additional-info-percentages">(20.0%)</span></td>
							<td><span>2</span><br> <span
								class="additional-info-percentages">(40.0%)</span></td>
							<td><span>2</span><br> <span
								class="additional-info-percentages">(40.0%)</span></td>
							<td><span>5</span><br> <span
								class="additional-info-percentages">(100%)</span></td>
						</tr>
					</tbody>
				</table>
			</section>

			<section
				id="site-risk-counts">
				<h3>Alert counts by site and risk</h3>
				<table class="site-risk-counts-table">
					<caption>
						<p>This table shows, for each site for which one or more alerts were raised, the number of alerts raised at each risk level.</p>
						<p>Alerts with a confidence level of &quot;False Positive&quot; have been excluded from these counts.</p>
						<p>(The numbers in brackets are the number of alerts raised for the site at or above that risk level.)</p>
					</caption>
					<colgroup>
						<col>
						<col>
					</colgroup>
					<colgroup>
						<col
							style="width: 16.25%"><col
							style="width: 16.25%"><col
							style="width: 16.25%"><col
							style="width: 16.25%">
					</colgroup>
					<thead>
						<tr>
							<td colspan="2" rowspan="2"></td>
							<th scope="colgroup" colspan="4">Risk</th>
						</tr>
						<tr>
							<th scope="col">
								<span>High</span><br>  <span
									class="additional-info-percentages">(= High)</span>  
							</th>
							<th scope="col">
								<span>Medium</span><br>   <span
									class="additional-info-percentages">(&gt;= Medium)</span> 
							</th>
							<th scope="col">
								<span>Low</span><br>   <span
									class="additional-info-percentages">(&gt;= Low)</span> 
							</th>
							<th scope="col">
								<span>Informational</span><br>   <span
									class="additional-info-percentages">(&gt;= Informational)</span> 
							</th>
						</tr>
					</thead>
					<tbody>
						<tr>
							<th scope="rowgroup"
								rowspan="1">Site</th>
							<th scope="row">http://localhost:8080</th>
							
							<td><span>0</span><br> <span
								class="additional-info-percentages">(0)</span></td>
							<td><span>1</span><br> <span
								class="additional-info-percentages">(1)</span></td>
							<td><span>0</span><br> <span
								class="additional-info-percentages">(1)</span></td>
							<td><span>4</span><br> <span
								class="additional-info-percentages">(5)</span></td>
							
						</tr>
					</tbody>
				</table>
			</section>

			<section
				id="alert-type-counts">
				<h3>Alert counts by alert type</h3>
				<table class="alert-type-counts-table">
					<caption>
						<p>This table shows the number of alerts of each alert type, together with the alert type&#39;s risk level.</p>
						<p>(The percentages in brackets represent each count as a percentage, rounded to one decimal place, of the total number of alerts included in this report.)</p>
					</caption>
					<thead>
						<tr>
							<th scope="col">Alert type</th>
							<th scope="col">Risk</th>
							<th scope="col">Count</th>
						</tr>
					</thead>
					<tbody>
						<tr>
							<th scope="row"><a
								href="#alert-type-0">CSP: Wildcard Directive</a></th>
							<td class="risk-level">Medium</td>
							<td><span>1442</span><br> <span
								class="additional-info-percentages">(28,840.0%)</span></td>
						</tr>
						<tr>
							<th scope="row"><a
								href="#alert-type-1">Authentication Request Identified</a></th>
							<td class="risk-level">Informational</td>
							<td><span>2</span><br> <span
								class="additional-info-percentages">(40.0%)</span></td>
						</tr>
						<tr>
							<th scope="row"><a
								href="#alert-type-2">Information Disclosure - Sensitive Information in URL</a></th>
							<td class="risk-level">Informational</td>
							<td><span>42</span><br> <span
								class="additional-info-percentages">(840.0%)</span></td>
						</tr>
						<tr>
							<th scope="row"><a
								href="#alert-type-3">User Agent Fuzzer</a></th>
							<td class="risk-level">Informational</td>
							<td><span>27156</span><br> <span
								class="additional-info-percentages">(543,120.0%)</span></td>
						</tr>
						<tr>
							<th scope="row"><a
								href="#alert-type-4">User Controllable HTML Element Attribute (Potential XSS)</a></th>
							<td class="risk-level">Informational</td>
							<td><span>4339</span><br> <span
								class="additional-info-percentages">(86,780.0%)</span></td>
						</tr>
					</tbody>
					<tfoot>
						<tr>
							<th scope="row">Total</th>
							<td></td>
							<td>5</td>
						</tr>
					</tfoot>
				</table>
			</section>
		</section>

		<section id="alerts" class="alerts">
			<h2>Alerts</h2>
			<ol>
				
				 
				 
				
				
				<li id="alerts--risk-2-confidence-3">
					<h3>
						<span>Risk</span>=<span
							class="risk-level">Medium</span>, <span>Confidence</span>=<span
							class="confidence-level">High</span> <span>(1)</span>
					</h3>
					<ol>
						
						<li class="alerts--site-li">
							<h4>
								<span class="site">http://localhost:8080</span> <span>(1)</span>
							</h4>
							<ol>
								
								<li>
									<h5>
										<a
											href="#alert-type-0">CSP: Wildcard Directive</a> <span>(1)</span>
									</h5>
									<ol>
										<li><details>
												<summary>
													<span class="request-method-n-url">GET http://localhost:8080/OTHER/network/other/proxy.pac/?apinonce=1cd884ae98fac895</span>
												</summary>
												
<table class="alerts-table">
	<tr>
		<th scope="row">Alert tags</th>
		<td>
			<ul class="alert-tags-list">
				<li>
					<span><a href="https://cwe.mitre.org/data/definitions/693.html">CWE-693</a></span> 
				</li>
				<li>
					<span><a href="https://owasp.org/Top10/A05_2021-Security_Misconfiguration/">OWASP_2021_A05</a></span> 
				</li>
				<li>
					<span><a href="https://owasp.org/www-project-top-ten/2017/A6_2017-Security_Misconfiguration.html">OWASP_2017_A06</a></span> 
				</li>
			</ul>
		</td>
	</tr>
	<tr>
		<th scope="row">Alert description</th>
		<td> 
<p>Content Security Policy (CSP) is an added layer of security that helps to detect and mitigate certain types of attacks. Including (but not limited to) Cross Site Scripting (XSS), and data injection attacks. These attacks are used for everything from data theft to site defacement or distribution of malware. CSP provides a set of standard HTTP headers that allow website owners to declare approved sources of content that browsers should be allowed to load on that page — covered types are JavaScript, CSS, HTML frames, fonts, images and embeddable objects such as Java applets, ActiveX, audio and video files.</p>
 </td>
	</tr>
	<tr>
		<th scope="row">Other info</th>
		<td> 
<p>The following directives either allow wildcard sources (or ancestors), are not defined, or are overly broadly defined:</p>

<p>frame-ancestors, form-action</p>

<p>The directive(s): frame-ancestors, form-action are among the directives that do not fallback to default-src, missing/excluding them is the same as allowing anything.</p>
 </td>
	</tr>
	<tr>
		<th scope="row">Request</th>
		<td><details open="open">
				<summary>Request line and header section (317 bytes)</summary>
				
				<pre><code>GET http://localhost:8080/OTHER/network/other/proxy.pac/?apinonce=1cd884ae98fac895 HTTP/1.1
host: localhost:8080
user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
pragma: no-cache
cache-control: no-cache
referer: http://localhost:8080

</code></pre>
				
				
			</details> <details class="request-body" open="open">
				<summary>Request body (0 bytes)</summary>
				
				<pre><code></code></pre>
				
				
			</details></td>
	</tr>
	<tr>
		<th scope="row">Response</th>
		<td><details open="open">
				<summary>Status line and header section (548 bytes)</summary>
				
				<pre><code>HTTP/1.1 200 OK
Pragma: no-cache
Cache-Control: no-cache, no-store, must-revalidate
Content-Security-Policy: default-src &#39;none&#39;; script-src &#39;self&#39;; connect-src &#39;self&#39;; child-src &#39;self&#39;; img-src &#39;self&#39; data:; font-src &#39;self&#39; data:; style-src &#39;self&#39;
Referrer-Policy: no-referrer
Access-Control-Allow-Methods: GET,POST,OPTIONS
Access-Control-Allow-Headers: ZAP-Header
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Clacks-Overhead: GNU Terry Pratchett
Content-Length: 92
Content-Type: text/html

</code></pre>
				
				
			</details> <details class="response-body" open="open">
				<summary>Response body (92 bytes)</summary>
				
				<pre><code>function FindProxyForURL(url, host) {
  return &quot;PROXY localhost:8080&quot;;
} // End of function
</code></pre>
				
				
			</details></td>
	</tr>
	<tr>
		<th scope="row">Parameter</th>
		<td><pre><code>Content-Security-Policy</code></pre></td>
	</tr>
	
	<tr>
		<th scope="row">Evidence</th>
		<td><pre><code>default-src &#39;none&#39;; script-src &#39;self&#39;; connect-src &#39;self&#39;; child-src &#39;self&#39;; img-src &#39;self&#39; data:; font-src &#39;self&#39; data:; style-src &#39;self&#39;</code></pre></td>
	</tr>
	<tr>
		<th scope="row">Solution</th>
		<td> 
<p>Ensure that your web server, application server, load balancer, etc. is properly configured to set the Content-Security-Policy header.</p>
 </td>
	</tr>
</table>

											</details></li>
									</ol>
								</li>
								
							</ol>
						</li>
						
					</ol>
				</li>
				
				
				
				
				  
				 
				 
				
				
				
				
				<li id="alerts--risk-0-confidence-2">
					<h3>
						<span>Risk</span>=<span
							class="risk-level">Informational</span>, <span>Confidence</span>=<span
							class="confidence-level">Medium</span> <span>(2)</span>
					</h3>
					<ol>
						
						<li class="alerts--site-li">
							<h4>
								<span class="site">http://localhost:8080</span> <span>(2)</span>
							</h4>
							<ol>
								
								<li>
									<h5>
										<a
											href="#alert-type-2">Information Disclosure - Sensitive Information in URL</a> <span>(1)</span>
									</h5>
									<ol>
										<li><details>
												<summary>
													<span class="request-method-n-url">GET http://localhost:8080/UI/forcedUser/action/setForcedUser/override?apikey=ZAP&amp;contextId=ZAP&amp;userId=ZAP</span>
												</summary>
												
<table class="alerts-table">
	<tr>
		<th scope="row">Alert tags</th>
		<td>
			<ul class="alert-tags-list">
				<li>
					<span><a href="https://cwe.mitre.org/data/definitions/598.html">CWE-598</a></span> 
				</li>
				<li>
					<span><a href="https://owasp.org/Top10/A01_2021-Broken_Access_Control/">OWASP_2021_A01</a></span> 
				</li>
				<li>
					<span><a href="https://owasp.org/www-project-top-ten/2017/A3_2017-Sensitive_Data_Exposure.html">OWASP_2017_A03</a></span> 
				</li>
			</ul>
		</td>
	</tr>
	<tr>
		<th scope="row">Alert description</th>
		<td> 
<p>The request appeared to contain sensitive information leaked in the URL. This can violate PCI and most organizational compliance policies. You can configure the list of strings for this check to add or remove values specific to your environment.</p>
 </td>
	</tr>
	<tr>
		<th scope="row">Other info</th>
		<td> 
<p>The URL contains potentially sensitive information. The following string was found via the pattern: user</p>

<p>userId</p>
 </td>
	</tr>
	<tr>
		<th scope="row">Request</th>
		<td><details open="open">
				<summary>Request line and header section (376 bytes)</summary>
				
				<pre><code>GET http://localhost:8080/UI/forcedUser/action/setForcedUser/override?apikey=ZAP&amp;contextId=ZAP&amp;userId=ZAP HTTP/1.1
host: localhost:8080
user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
pragma: no-cache
cache-control: no-cache
referer: http://localhost:8080/UI/forcedUser/action/setForcedUser/

</code></pre>
				
				
			</details> <details class="request-body" open="open">
				<summary>Request body (0 bytes)</summary>
				
				<pre><code></code></pre>
				
				
			</details></td>
	</tr>
	<tr>
		<th scope="row">Response</th>
		<td><details open="open">
				<summary>Status line and header section (565 bytes)</summary>
				
				<pre><code>HTTP/1.1 200 OK
Pragma: no-cache
Cache-Control: no-cache, no-store, must-revalidate
Content-Security-Policy: default-src &#39;none&#39;; script-src &#39;self&#39;; connect-src &#39;self&#39;; child-src &#39;self&#39;; img-src &#39;self&#39; data:; font-src &#39;self&#39; data:; style-src &#39;self&#39;
Referrer-Policy: no-referrer
Access-Control-Allow-Methods: GET,POST,OPTIONS
Access-Control-Allow-Headers: ZAP-Header
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Clacks-Overhead: GNU Terry Pratchett
content-length: 1270
Content-Type: text/html; charset=UTF-8

</code></pre>
				
				
			</details> <details class="response-body" open="open">
				<summary>Response body (1270 bytes)</summary>
				
				<pre><code>&lt;!DOCTYPE html&gt;
&lt;head&gt;
&lt;title&gt;ZAP API UI&lt;/title&gt;
&lt;script src=&quot;/script.js/?v=2&amp;apinonce=9972443b64a4b952&quot; type=&quot;text/javascript&quot;&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;h1&gt;&lt;a href=&quot;/UI/&quot;&gt;ZAP API UI&lt;/a&gt;&lt;/h1&gt;
&lt;h2&gt;&lt;a href=&quot;/UI/forcedUser/&quot;&gt;Component: forcedUser&lt;/a&gt;&lt;/h2&gt;
&lt;h3&gt;Action: setForcedUser&lt;/h3&gt;
Sets the user (ID) that should be used in &#39;forced user&#39; mode for the given context (ID)
&lt;form id=&quot;zapform&quot; name=&quot;zapform&quot; action=&quot;override&quot;&gt;&lt;table&gt;
&lt;tr&gt;&lt;td&gt;Output Format&lt;/td&gt;&lt;td&gt;
&lt;select id=&quot;zapapiformat&quot;&gt;
&lt;option value=&quot;JSON&quot;&gt;JSON&lt;/option&gt;
&lt;option value=&quot;JSONP&quot; disabled&gt;JSONP&lt;/option&gt;
&lt;option value=&quot;HTML&quot;&gt;HTML&lt;/option&gt;
&lt;option value=&quot;XML&quot;&gt;XML&lt;/option&gt;
&lt;/select&gt;
&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;apikey*&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;apikey&quot; name=&quot;apikey&quot; value=&quot;&quot;/&gt;&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Form Method&lt;/td&gt;&lt;td&gt;&lt;select id=&quot;formMethod&quot;&gt;
&lt;option value=&quot;GET&quot; selected&gt;GET&lt;/option&gt;
&lt;option value=&quot;POST&quot;&gt;POST&lt;/option&gt;
&lt;/select&gt;
&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;contextId*&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;contextId&quot; name=&quot;contextId&quot;/&gt;&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;userId*&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;userId&quot; name=&quot;userId&quot;/&gt;&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;button&quot; value=&quot;setForcedUser&quot; type=&quot;submit&quot; zap-component=&quot;forcedUser&quot; zap-type=&quot;action&quot; zap-name=&quot;setForcedUser&quot;/&gt;
&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;/table&gt;
&lt;/form&gt;
&lt;/body&gt;
</code></pre>
				
				
			</details></td>
	</tr>
	<tr>
		<th scope="row">Parameter</th>
		<td><pre><code>userId</code></pre></td>
	</tr>
	
	<tr>
		<th scope="row">Evidence</th>
		<td><pre><code>userId</code></pre></td>
	</tr>
	<tr>
		<th scope="row">Solution</th>
		<td> 
<p>Do not pass sensitive information in URIs.</p>
 </td>
	</tr>
</table>

											</details></li>
									</ol>
								</li>
								
								<li>
									<h5>
										<a
											href="#alert-type-3">User Agent Fuzzer</a> <span>(1)</span>
									</h5>
									<ol>
										<li><details>
												<summary>
													<span class="request-method-n-url">GET http://localhost:8080/OTHER</span>
												</summary>
												
<table class="alerts-table">
	<tr>
		<th scope="row">Alert tags</th>
		<td>
			<ul class="alert-tags-list">
				
			</ul>
		</td>
	</tr>
	<tr>
		<th scope="row">Alert description</th>
		<td> 
<p>Check for differences in response based on fuzzed User Agent (eg. mobile sites, access as a Search Engine Crawler). Compares the response statuscode and the hashcode of the response body with the original response.</p>
 </td>
	</tr>
	
	<tr>
		<th scope="row">Request</th>
		<td><details open="open">
				<summary>Request line and header section (205 bytes)</summary>
				
				<pre><code>GET http://localhost:8080/OTHER HTTP/1.1
host: localhost:8080
user-agent: Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1)
pragma: no-cache
cache-control: no-cache
referer: http://localhost:8080

</code></pre>
				
				
			</details> <details class="request-body" open="open">
				<summary>Request body (0 bytes)</summary>
				
				<pre><code></code></pre>
				
				
			</details></td>
	</tr>
	<tr>
		<th scope="row">Response</th>
		<td><details open="open">
				<summary>Status line and header section (565 bytes)</summary>
				
				<pre><code>HTTP/1.1 200 OK
Pragma: no-cache
Cache-Control: no-cache, no-store, must-revalidate
Content-Security-Policy: default-src &#39;none&#39;; script-src &#39;self&#39;; connect-src &#39;self&#39;; child-src &#39;self&#39;; img-src &#39;self&#39; data:; font-src &#39;self&#39; data:; style-src &#39;self&#39;
Referrer-Policy: no-referrer
Access-Control-Allow-Methods: GET,POST,OPTIONS
Access-Control-Allow-Headers: ZAP-Header
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Clacks-Overhead: GNU Terry Pratchett
content-length: 1525
Content-Type: text/html; charset=UTF-8

</code></pre>
				
				
			</details> <details class="response-body" open="open">
				<summary>Response body (1525 bytes)</summary>
				
				<pre><code>&lt;head&gt;
&lt;title&gt;ZAP API UI&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;h1&gt;Welcome to the Zed Attack Proxy (ZAP)&lt;/h1&gt;&lt;p&gt;ZAP is an easy to use integrated penetration testing tool for finding vulnerabilities in web applications.&lt;/p&gt;&lt;p&gt;&lt;/p&gt;&lt;p&gt;Please be aware that you should only attack applications that you have been specifically been given permission to test.&lt;/p&gt;&lt;h2&gt;Proxy Configuration&lt;/h2&gt;&lt;p&gt;To use ZAP effectively it is recommended that you configure your browser to proxy via ZAP.&lt;/p&gt;&lt;p&gt;&lt;/p&gt;&lt;p&gt;The easiest way to do this is to launch your browser from ZAP via the &quot;Quick Start / Manual Explore&quot; panel - it will be configured to proxy via ZAP and ignore any certificate warnings.&lt;br&gt;Alternatively, you can configure your browser manually, or use the generated &lt;a href=&quot;/OTHER/network/other/proxy.pac/?apinonce=44938423026a52b&quot;&gt;PAC file&lt;/a&gt;.&lt;/p&gt;&lt;h2&gt;HTTPS Warnings Prevention&lt;/h2&gt;&lt;p&gt;To avoid HTTPS Warnings &lt;a href=&quot;/OTHER/network/other/rootCaCert/?apinonce=ce8b0c5206c24212&quot;&gt;download&lt;/a&gt; and &lt;a href=&quot;https://www.zaproxy.org/docs/desktop/addons/network/options/servercertificates/#install&quot; target=&quot;_blank&quot;&gt;install CA root Certificate&lt;/a&gt; in your Mobile device or computer.&lt;/p&gt;&lt;h2&gt;Links&lt;/h2&gt;&lt;li&gt;&lt;a href=&quot;/UI&quot;&gt;Local API&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a href=&quot;https://www.zaproxy.org/&quot;&gt;ZAP Website&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a href=&quot;https://groups.google.com/group/zaproxy-users&quot;&gt;ZAP User Group&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a href=&quot;https://groups.google.com/group/zaproxy-develop&quot;&gt;ZAP Developer Group&lt;/a&gt;&lt;/li&gt;&lt;li&gt;&lt;a href=&quot;https://github.com/zaproxy/zaproxy/issues&quot;&gt;Report an issue&lt;/a&gt;&lt;/li&gt;&lt;/body&gt;
</code></pre>
				
				
			</details></td>
	</tr>
	<tr>
		<th scope="row">Parameter</th>
		<td><pre><code>Header User-Agent</code></pre></td>
	</tr>
	<tr>
		<th scope="row">Attack</th>
		<td><pre><code>Mozilla/4.0 (compatible; MSIE 8.0; Windows NT 6.1)</code></pre></td>
	</tr>
	
	
</table>

											</details></li>
									</ol>
								</li>
								
							</ol>
						</li>
						
					</ol>
				</li>
				
				<li id="alerts--risk-0-confidence-1">
					<h3>
						<span>Risk</span>=<span
							class="risk-level">Informational</span>, <span>Confidence</span>=<span
							class="confidence-level">Low</span> <span>(2)</span>
					</h3>
					<ol>
						
						<li class="alerts--site-li">
							<h4>
								<span class="site">http://localhost:8080</span> <span>(2)</span>
							</h4>
							<ol>
								
								<li>
									<h5>
										<a
											href="#alert-type-1">Authentication Request Identified</a> <span>(1)</span>
									</h5>
									<ol>
										<li><details>
												<summary>
													<span class="request-method-n-url">GET http://localhost:8080/UI/network/action/setHttpProxy/override?apikey=ZAP&amp;host=ZAP&amp;password=ZAP&amp;port=ZAP&amp;realm=ZAP&amp;username=ZAP</span>
												</summary>
												
<table class="alerts-table">
	<tr>
		<th scope="row">Alert tags</th>
		<td>
			<ul class="alert-tags-list">
				
			</ul>
		</td>
	</tr>
	<tr>
		<th scope="row">Alert description</th>
		<td> 
<p>The given request has been identified as an authentication request. The &#39;Other Info&#39; field contains a set of key=value lines which identify any relevant fields. If the request is in a context which has an Authentication Method set to &quot;Auto-Detect&quot; then this rule will change the authentication to match the request identified.</p>
 </td>
	</tr>
	<tr>
		<th scope="row">Other info</th>
		<td> 
<p>userParam=username</p>

<p>userValue=ZAP</p>

<p>passwordParam=password</p>

<p>referer=http://localhost:8080/UI/network/action/setHttpProxy/</p>
 </td>
	</tr>
	<tr>
		<th scope="row">Request</th>
		<td><details open="open">
				<summary>Request line and header section (397 bytes)</summary>
				
				<pre><code>GET http://localhost:8080/UI/network/action/setHttpProxy/override?apikey=ZAP&amp;host=ZAP&amp;password=ZAP&amp;port=ZAP&amp;realm=ZAP&amp;username=ZAP HTTP/1.1
host: localhost:8080
user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
pragma: no-cache
cache-control: no-cache
referer: http://localhost:8080/UI/network/action/setHttpProxy/

</code></pre>
				
				
			</details> <details class="request-body" open="open">
				<summary>Request body (0 bytes)</summary>
				
				<pre><code></code></pre>
				
				
			</details></td>
	</tr>
	<tr>
		<th scope="row">Response</th>
		<td><details open="open">
				<summary>Status line and header section (565 bytes)</summary>
				
				<pre><code>HTTP/1.1 200 OK
Pragma: no-cache
Cache-Control: no-cache, no-store, must-revalidate
Content-Security-Policy: default-src &#39;none&#39;; script-src &#39;self&#39;; connect-src &#39;self&#39;; child-src &#39;self&#39;; img-src &#39;self&#39; data:; font-src &#39;self&#39; data:; style-src &#39;self&#39;
Referrer-Policy: no-referrer
Access-Control-Allow-Methods: GET,POST,OPTIONS
Access-Control-Allow-Headers: ZAP-Header
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Clacks-Overhead: GNU Terry Pratchett
content-length: 1511
Content-Type: text/html; charset=UTF-8

</code></pre>
				
				
			</details> <details class="response-body" open="open">
				<summary>Response body (1511 bytes)</summary>
				
				<pre><code>&lt;!DOCTYPE html&gt;
&lt;head&gt;
&lt;title&gt;ZAP API UI&lt;/title&gt;
&lt;script src=&quot;/script.js/?v=2&amp;apinonce=d8e5bcda94934e30&quot; type=&quot;text/javascript&quot;&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;h1&gt;&lt;a href=&quot;/UI/&quot;&gt;ZAP API UI&lt;/a&gt;&lt;/h1&gt;
&lt;h2&gt;&lt;a href=&quot;/UI/network/&quot;&gt;Component: network&lt;/a&gt;&lt;/h2&gt;
&lt;h3&gt;Action: setHttpProxy&lt;/h3&gt;
Sets the HTTP proxy configuration.
&lt;form id=&quot;zapform&quot; name=&quot;zapform&quot; action=&quot;override&quot;&gt;&lt;table&gt;
&lt;tr&gt;&lt;td&gt;Output Format&lt;/td&gt;&lt;td&gt;
&lt;select id=&quot;zapapiformat&quot;&gt;
&lt;option value=&quot;JSON&quot;&gt;JSON&lt;/option&gt;
&lt;option value=&quot;JSONP&quot; disabled&gt;JSONP&lt;/option&gt;
&lt;option value=&quot;HTML&quot;&gt;HTML&lt;/option&gt;
&lt;option value=&quot;XML&quot;&gt;XML&lt;/option&gt;
&lt;/select&gt;
&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;apikey*&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;apikey&quot; name=&quot;apikey&quot; value=&quot;&quot;/&gt;&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Form Method&lt;/td&gt;&lt;td&gt;&lt;select id=&quot;formMethod&quot;&gt;
&lt;option value=&quot;GET&quot; selected&gt;GET&lt;/option&gt;
&lt;option value=&quot;POST&quot;&gt;POST&lt;/option&gt;
&lt;/select&gt;
&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;host*&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;host&quot; name=&quot;host&quot;/&gt;&lt;/td&gt;&lt;td&gt;The host, name or address.&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;port*&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;port&quot; name=&quot;port&quot;/&gt;&lt;/td&gt;&lt;td&gt;The port.&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;realm&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;realm&quot; name=&quot;realm&quot;/&gt;&lt;/td&gt;&lt;td&gt;The authentication realm.&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;username&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;username&quot; name=&quot;username&quot;/&gt;&lt;/td&gt;&lt;td&gt;The user name.&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;password&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;password&quot; name=&quot;password&quot;/&gt;&lt;/td&gt;&lt;td&gt;The password.&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;button&quot; value=&quot;setHttpProxy&quot; type=&quot;submit&quot; zap-component=&quot;network&quot; zap-type=&quot;action&quot; zap-name=&quot;setHttpProxy&quot;/&gt;
&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;/table&gt;
&lt;/form&gt;
&lt;/body&gt;
</code></pre>
				
				
			</details></td>
	</tr>
	<tr>
		<th scope="row">Parameter</th>
		<td><pre><code>username</code></pre></td>
	</tr>
	
	<tr>
		<th scope="row">Evidence</th>
		<td><pre><code>password</code></pre></td>
	</tr>
	<tr>
		<th scope="row">Solution</th>
		<td> 
<p>This is an informational alert rather than a vulnerability and so there is nothing to fix.</p>
 </td>
	</tr>
</table>

											</details></li>
									</ol>
								</li>
								
								<li>
									<h5>
										<a
											href="#alert-type-4">User Controllable HTML Element Attribute (Potential XSS)</a> <span>(1)</span>
									</h5>
									<ol>
										<li><details>
												<summary>
													<span class="request-method-n-url">GET http://localhost:8080/UI/authentication/view/getAuthenticationMethod/override?apikey=ZAP&amp;contextId=ZAP</span>
												</summary>
												
<table class="alerts-table">
	<tr>
		<th scope="row">Alert tags</th>
		<td>
			<ul class="alert-tags-list">
				<li>
					<span><a href="https://owasp.org/www-project-top-ten/2017/A1_2017-Injection.html">OWASP_2017_A01</a></span> 
				</li>
				<li>
					<span><a href="https://cwe.mitre.org/data/definitions/20.html">CWE-20</a></span> 
				</li>
				<li>
					<span><a href="https://owasp.org/Top10/A03_2021-Injection/">OWASP_2021_A03</a></span> 
				</li>
			</ul>
		</td>
	</tr>
	<tr>
		<th scope="row">Alert description</th>
		<td> 
<p>This check looks at user-supplied input in query string parameters and POST data to identify where certain HTML attribute values might be controlled. This provides hot-spot detection for XSS (cross-site scripting) that will require further review by a security analyst to determine exploitability.</p>
 </td>
	</tr>
	<tr>
		<th scope="row">Other info</th>
		<td> 
<p>User-controlled HTML attribute values were found. Try injecting special characters to see if XSS might be possible. The page at the following URL:</p>

<p>http://localhost:8080/UI/authentication/view/getAuthenticationMethod/override?apikey=ZAP&amp;contextId=ZAP</p>

<p>appears to include user input in:</p>

<p>a(n) [form] tag [id] attribute</p>

<p>The user input found was:</p>

<p>apikey=ZAP</p>

<p>The user-controlled value was:</p>

<p>zapform</p>
 </td>
	</tr>
	<tr>
		<th scope="row">Request</th>
		<td><details open="open">
				<summary>Request line and header section (389 bytes)</summary>
				
				<pre><code>GET http://localhost:8080/UI/authentication/view/getAuthenticationMethod/override?apikey=ZAP&amp;contextId=ZAP HTTP/1.1
host: localhost:8080
user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/131.0.0.0 Safari/537.36
pragma: no-cache
cache-control: no-cache
referer: http://localhost:8080/UI/authentication/view/getAuthenticationMethod/

</code></pre>
				
				
			</details> <details class="request-body" open="open">
				<summary>Request body (0 bytes)</summary>
				
				<pre><code></code></pre>
				
				
			</details></td>
	</tr>
	<tr>
		<th scope="row">Response</th>
		<td><details open="open">
				<summary>Status line and header section (565 bytes)</summary>
				
				<pre><code>HTTP/1.1 200 OK
Pragma: no-cache
Cache-Control: no-cache, no-store, must-revalidate
Content-Security-Policy: default-src &#39;none&#39;; script-src &#39;self&#39;; connect-src &#39;self&#39;; child-src &#39;self&#39;; img-src &#39;self&#39; data:; font-src &#39;self&#39; data:; style-src &#39;self&#39;
Referrer-Policy: no-referrer
Access-Control-Allow-Methods: GET,POST,OPTIONS
Access-Control-Allow-Headers: ZAP-Header
X-Frame-Options: DENY
X-XSS-Protection: 1; mode=block
X-Content-Type-Options: nosniff
X-Clacks-Overhead: GNU Terry Pratchett
content-length: 1219
Content-Type: text/html; charset=UTF-8

</code></pre>
				
				
			</details> <details class="response-body" open="open">
				<summary>Response body (1219 bytes)</summary>
				
				<pre><code>&lt;!DOCTYPE html&gt;
&lt;head&gt;
&lt;title&gt;ZAP API UI&lt;/title&gt;
&lt;script src=&quot;/script.js/?v=2&amp;apinonce=4e96ad8743c0e1b4&quot; type=&quot;text/javascript&quot;&gt;&lt;/script&gt;
&lt;/head&gt;
&lt;body&gt;
&lt;h1&gt;&lt;a href=&quot;/UI/&quot;&gt;ZAP API UI&lt;/a&gt;&lt;/h1&gt;
&lt;h2&gt;&lt;a href=&quot;/UI/authentication/&quot;&gt;Component: authentication&lt;/a&gt;&lt;/h2&gt;
&lt;h3&gt;View:getAuthenticationMethod&lt;/h3&gt;
Gets the name of the authentication method for the context with the given ID.
&lt;form id=&quot;zapform&quot; name=&quot;zapform&quot; action=&quot;override&quot;&gt;&lt;table&gt;
&lt;tr&gt;&lt;td&gt;Output Format&lt;/td&gt;&lt;td&gt;
&lt;select id=&quot;zapapiformat&quot;&gt;
&lt;option value=&quot;JSON&quot;&gt;JSON&lt;/option&gt;
&lt;option value=&quot;JSONP&quot; disabled&gt;JSONP&lt;/option&gt;
&lt;option value=&quot;HTML&quot;&gt;HTML&lt;/option&gt;
&lt;option value=&quot;XML&quot;&gt;XML&lt;/option&gt;
&lt;/select&gt;
&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;apikey*&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;apikey&quot; name=&quot;apikey&quot; value=&quot;&quot;/&gt;&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;Form Method&lt;/td&gt;&lt;td&gt;&lt;select id=&quot;formMethod&quot;&gt;
&lt;option value=&quot;GET&quot; selected&gt;GET&lt;/option&gt;
&lt;option value=&quot;POST&quot;&gt;POST&lt;/option&gt;
&lt;/select&gt;
&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;contextId*&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;contextId&quot; name=&quot;contextId&quot;/&gt;&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;tr&gt;&lt;td&gt;&lt;/td&gt;&lt;td&gt;&lt;input id=&quot;button&quot; value=&quot;getAuthenticationMethod&quot; type=&quot;submit&quot; zap-component=&quot;authentication&quot; zap-type=&quot;view&quot; zap-name=&quot;getAuthenticationMethod&quot;/&gt;
&lt;/td&gt;&lt;td&gt;&lt;/td&gt;&lt;/tr&gt;
&lt;/table&gt;
&lt;/form&gt;
&lt;/body&gt;
</code></pre>
				
				
			</details></td>
	</tr>
	<tr>
		<th scope="row">Parameter</th>
		<td><pre><code>apikey</code></pre></td>
	</tr>
	
	
	<tr>
		<th scope="row">Solution</th>
		<td> 
<p>Validate all input and sanitize output it before writing to any HTML attributes.</p>
 </td>
	</tr>
</table>

											</details></li>
									</ol>
								</li>
								
							</ol>
						</li>
						
					</ol>
				</li>
				  
			</ol>
		</section>

		<section id="appendix" class="appendix">
			<h2>Appendix</h2>

			<section id="alert-types" class="alert-types">
				<h3>Alert types</h3>
				<p class="alert-types-intro">This section contains additional information on the types of alerts in the report.</p>
				<ol>
					<li
						id="alert-type-0">
						<h4>CSP: Wildcard Directive</h4>
						<table class="alert-types-table">
							<tr>
								<th scope="row">Source</th>
								<td>
									
									   <span>raised by a passive scanner</span> <span>(<a
										href="https://www.zaproxy.org/docs/alerts/10055/">CSP</a>)
									</span>   
								</td>
							</tr>
							<tr>
								<th scope="row">CWE ID</th>
								<td><a
									href="https://cwe.mitre.org/data/definitions/693.html">693</a></td>
							</tr>
							<tr>
								<th scope="row">WASC ID</th>
								<td>15</td>
							</tr>
							<tr>
								<th scope="row">Reference</th>
								<td>
									<ol>
										<li><a
											href="https://www.w3.org/TR/CSP/">https://www.w3.org/TR/CSP/</a></li>
										<li><a
											href="https://caniuse.com/#search=content+security+policy">https://caniuse.com/#search=content+security+policy</a></li>
										<li><a
											href="https://content-security-policy.com/">https://content-security-policy.com/</a></li>
										<li><a
											href="https://github.com/HtmlUnit/htmlunit-csp">https://github.com/HtmlUnit/htmlunit-csp</a></li>
										<li><a
											href="https://developers.google.com/web/fundamentals/security/csp#policy_applies_to_a_wide_variety_of_resources">https://developers.google.com/web/fundamentals/security/csp#policy_applies_to_a_wide_variety_of_resources</a></li>
									</ol>
								</td>
							</tr>
						</table>
					</li>
					<li
						id="alert-type-1">
						<h4>Authentication Request Identified</h4>
						<table class="alert-types-table">
							<tr>
								<th scope="row">Source</th>
								<td>
									
									   <span>raised by a passive scanner</span> <span>(<a
										href="https://www.zaproxy.org/docs/alerts/10111/">Authentication Request Identified</a>)
									</span>   
								</td>
							</tr>
							
							
							<tr>
								<th scope="row">Reference</th>
								<td>
									<ol>
										<li><a
											href="https://www.zaproxy.org/docs/desktop/addons/authentication-helper/auth-req-id/">https://www.zaproxy.org/docs/desktop/addons/authentication-helper/auth-req-id/</a></li>
									</ol>
								</td>
							</tr>
						</table>
					</li>
					<li
						id="alert-type-2">
						<h4>Information Disclosure - Sensitive Information in URL</h4>
						<table class="alert-types-table">
							<tr>
								<th scope="row">Source</th>
								<td>
									
									   <span>raised by a passive scanner</span> <span>(<a
										href="https://www.zaproxy.org/docs/alerts/10024/">Information Disclosure - Sensitive Information in URL</a>)
									</span>   
								</td>
							</tr>
							<tr>
								<th scope="row">CWE ID</th>
								<td><a
									href="https://cwe.mitre.org/data/definitions/598.html">598</a></td>
							</tr>
							<tr>
								<th scope="row">WASC ID</th>
								<td>13</td>
							</tr>
							
						</table>
					</li>
					<li
						id="alert-type-3">
						<h4>User Agent Fuzzer</h4>
						<table class="alert-types-table">
							<tr>
								<th scope="row">Source</th>
								<td>
									
									   <span>raised by an active scanner</span> <span>(<a
										href="https://www.zaproxy.org/docs/alerts/10104/">User Agent Fuzzer</a>)
									</span>   
								</td>
							</tr>
							
							
							<tr>
								<th scope="row">Reference</th>
								<td>
									<ol>
										<li><a
											href="https://owasp.org/wstg">https://owasp.org/wstg</a></li>
									</ol>
								</td>
							</tr>
						</table>
					</li>
					<li
						id="alert-type-4">
						<h4>User Controllable HTML Element Attribute (Potential XSS)</h4>
						<table class="alert-types-table">
							<tr>
								<th scope="row">Source</th>
								<td>
									
									   <span>raised by a passive scanner</span> <span>(<a
										href="https://www.zaproxy.org/docs/alerts/10031/">User Controllable HTML Element Attribute (Potential XSS)</a>)
									</span>   
								</td>
							</tr>
							<tr>
								<th scope="row">CWE ID</th>
								<td><a
									href="https://cwe.mitre.org/data/definitions/20.html">20</a></td>
							</tr>
							<tr>
								<th scope="row">WASC ID</th>
								<td>20</td>
							</tr>
							<tr>
								<th scope="row">Reference</th>
								<td>
									<ol>
										<li><a
											href="https://cheatsheetseries.owasp.org/cheatsheets/Input_Validation_Cheat_Sheet.html">https://cheatsheetseries.owasp.org/cheatsheets/Input_Validation_Cheat_Sheet.html</a></li>
									</ol>
								</td>
							</tr>
						</table>
					</li>
				</ol>
			</section>
		</section>
		 
	</main>
</body>
</html>



