#  Pricing FAQ


## 1. How much does the "{{product.name}}" license cost?

<div style="
    font-weight: bold;
    font-size: 1.2em;
    text-align: center;
    padding: 10px;
    background-color: #d6d6d6;
    margin: 40px;
"> Flat price: EUR 99 per server per year! </div>

* Support and Maintenance included in the subscription
* Paid annually 
* No user limit
* Evaluation license available

<br/>
<a href="#getquote">
<button class="mdc-button">&nbsp;Get official Quote!&nbsp;</button>
</a>
</center>

<div class="who-banner" >
<b><i>Why to pay and not develop in house?</i></b>
<p>
Our experts bring the 14 years experience of design and implementation of various customizations while remaining aligned to core Polarion principles.
</p>
<p>
The <b>usability</b> and <b>performance</b> is not an afterthought, but considered right from the early design phases.
</p>
<p>
We maintain the plugins for big number of Polarion customers, with  <b>Support & Maintenance</b> contract we guarantee that the plugins keep working well in the future.
</p>
</div>

## 2. What is covered by Support & Maintenance?

Software Support & Maintenance covers the following benefits:

* Critical **bug fixes**
* Update to **new versions** of the SW and benefit from new features & enhancements
* Access our experienced Support team for **technical troubleshooting**
* **Staging server** license key (to be requested separately)
* Optional participation in **Early Access Programs**





## 3. What are the license terms?
A valid commercial license entitles you to:

* Install *{{product.name}}* Software on a single instance in a production environment on **1 Polarion server** (including load balanced clustered server)
* Benefit from Software Support & Maintenance - including all updates and online support

Detailed conditions available [here]({{product.url}}/download/LICENSE.pdf).

## 4. Is there trial license available 

The evaluation license is included in the distribution. You can download the product and **evaluate** it free of charge for **30 days**.

<a name="getquote">&nbsp;</a>

## 5. How do I purchase a license?

Start by requesting a no-obligation quote valid for next 30 days:

<script charset="utf-8" type="text/javascript" src="//js.hsforms.net/forms/shell.js"></script>
<script>
  hbspt.forms.create({
	portalId: "{{hs.id}}",
	formId: "{{hs.quoteFormId}}"
});
</script>


### Cannot get a quote?

We have experienced that some privacy browser add-ons are blocking our CRM System HubSpot (Although we  follow the privacy recommendations and we support GDPR standard). 
	
	
If you cannot submit the quote form from our website - please write us an email to <a href="mailto:info@nextedy.com">info@nextedy.com</a>
 

<script>
function setSizes(){
	console.log("setting style ...");
   	var style = "<style>.hubspot-link__container{display:none;}.submitted-message{border: 1px solid #ff7a59;padding: 10px;font-weight: bold;background-color: #ffe6e0;}.hs-input{background-color: white;border: 1px solid #f9bbac;}label{font-weight:bold;}legend{    color: #33475b !important;}</style>";
	$("#hs-form-iframe-0").contents().find(".hbspt-form").first().prepend(style);
	console.log("setting style DONE");
}
var i = 0;
var findHSForm = function(){
	i++;
	console.log("findHSForm:"+i);
	var loaded = $("#hs-form-iframe-0").contents().find(".hubspot-link__container").length;
	console.log(" - " + loaded + " hs form.");	
    if(loaded>0){
	    		setTimeout(setSizes, 10); 	 	
    }else {
    		if(i<100){
	    		setTimeout(findHSForm, 100); 	 	
    		}
    }
}
findHSForm();
</script>






