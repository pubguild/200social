+++
date = "2016-07-09T19:40:19Z"
draft = false
title = "Contact"

+++

<div id='crmWebToEntityForm'>
<META HTTP-EQUIV ='content-type' CONTENT='text/html;charset=UTF-8'>

<form action='https://crm.zoho.com/crm/WebToLeadForm' 
	name=WebToLeads2015827000000104023 method='POST' 
	onSubmit='javascript:document.charset="UTF-8"; return checkMandatory()' 
	accept-charset='UTF-8'>

	 <!-- Do not remove this code. -->
	<input type='text' style='display:none;' name='xnQsjsdp' value='670cbb754cef376380a8265570fb68c7df5f3e6204d431b7146d5bccf526d56b'/>
	<input type='hidden' name='zc_gad' id='zc_gad' value=''/>
	<!-- <input type='text' style='display:none;' name='xmIwtLD' value='d34dc902754bbad7bfd1b82d9ff6391147850e633327dc0168830469c459c195'/> -->
	<input type='text' style='display:none;' name='xmIwtLD' value='d34dc902754bbad7bfd1b82d9ff639116ed04a606f9816fe2a3471b654886c1c'/>
	<input type='text' style='display:none;'  name='actionType' value='TGVhZHM='/>

	<input type='text' style='display:none;' name='returnURL' value='http&#x3a;&#x2f;&#x2f;tigoctm.com' /> 
	 <!-- Do not remove this code. -->
- More Info

- We will contact you within 24 hours. We look forward to making your brand stand out on the internet. We have a few procedures in place to make the most of your $200 Social experience. In order to accomplish this we like to get to know our clients before we take your order. We can communicate through Email, Phone, Twitter or Skype. Don’t forget to add us on Twitter, Facebook and Google Plus.

- Address: Panama

- Business Hours: 8am-4pm M-F
  <div class="form-row">
    <label for="firstname">Name
      <span class="form-error" id="error-name">Please specify your name</span>
    </label>
    <div class="form-half-row" style="padding-right: 2%">
      <input type="text" maxlength="40" name="First Name" id="firstname"
          placeholder="First">
    </div>
    <div class="form-half-row">
      <input type="text" maxlength="80" name="Last Name" id="lastname"
          placeholder="Last">
    </div>
  </div>

  <div class="form-row">
    <input type="text" maxlength="100" name="Email" id="email"
    	   placeholder="Email">
    <span class="form-error" id="error-email">
        Please specify your email so we can communicate with you
    </span>
  </div>

  <div class="form-row">
    <label for="company">Company <span class="contact-info">optional</span></label>
    <input type="text" maxlength="100" name="Company" id="company">
  </div>

  <div class="form-row">
    <label for="shipping">Shipping <span class="contact-info">optional</span></label>
    <div class="form-half-row" style="padding-right: 2%">
    	 <input type="text" maxlength="80" name="Country" id="country"
          	placeholder="Country">
     </div>
     <div class="form-half-row">
      <input type="text" maxlength="40" name="City" id="city"
          placeholder="City">
  </div>

  <div class="form-row">
    <label for="message">Message
    <span class="form-error" id="error-message">
        We will need some message to know what you are after
    </span>
    </label>
    <textarea name="Description" id="message" cols="40" rows="10" maxlength="1000"></textarea>
   </div>

  <div class="form-align">
    <input type="submit" value="Request More Information">
  </div>
</div>

  <script>
    var fields = ['firstname', 'lastname', 'email', 'message', 'city', 'country'];
    var basicEmail = /^[^ @]+@([^ @]+){2,}\.([^ @]+){2,}$/;

    function checkMandatory() {
      /* Hide any errors. */
      var allErrors = document.getElementsByClassName('form-error');
      for (var i = 0; i < allErrors.length; i++) {
        allErrors[i].style.display = 'none';
      }

      /* Validate the form. */
      var form = document.forms['WebToLeads2015827000000104023'];
      for (var i = 0; i < fields.length; i++) {
        var fieldObj = form[fields[i]];
        if (fieldObj) {
          var failed = fieldObj.value.replace(/^\s+|\s+$/g, '').length === 0;
          if (!failed && fields[i] === 'email') {
            failed = !basicEmail.test(fieldObj.value);
          }

          if (failed) {
            fieldObj.focus();
            var name = fields[i];
            if (name.endsWith('name')) {
              name = 'name';
            }
            var err = document.getElementById('error-' + name);
            if (err) {
              err.style.display = 'block';
            }
            return false;
          }
        }
      }
    }
  </script>
<form>
</div>