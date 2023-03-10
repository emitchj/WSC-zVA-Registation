<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending this Washington Systems Center(WSC) workshop. 

## Accessing the hands-on lab

Click [here](https://github.com/emitchj/WSC-zVA-Registation/blob/gh-pages/Remote%20Lab%20System%20Connection%20Instructions.pdf) to read the instruction for accessing the IBM systems from your workstation.

Clink [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/blob/master/zva/Important-Read%20Me.pdf) for important information regarding credentials for accessing z/OS, the Designer containers as well as the 3270 emulator (Personal Communications) keyboard mappings for the **Enter** and **Clear** keys as well as information on how to customize the 3270 Personal Communications keyboard for use on Mac keyboards.

Exercises for generating OpenAPI 2 specification documents are available at Box@IBM [here](https://ibm.box.com/v/WSC-OpenAPi2) and/or at Github [here]( https://ibm.biz/BdPbPs).

Exercises for consuming OpenAPI 3 specification documents are available at Box@IBM [here](https://ibm.box.com/v/WSC-OpenAPI3) and/or at Github [here](https://ibm.biz/BdPbPb).

Exercises for the developing of z/OS Connect API Requester applications are available at Box@IBM [here](https://ibm.box.com/v/WSC-APIRequester) and/or Github [here](https://ibm.biz/BdPbPp).

Exercises related to the administration and security of z/OS Connect servers are available at Box@IBM [here](https://ibm.box.com/v/WSC-AdminSecurity) and/or Github [here](https://ibm.biz/BdPbPg).

The server XML configuration files referenced in the exercises can be downloaded from [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/tree/master/XML%20Samples) to view them locally.


**Please enter your email address used for registration to retrieve your unique log in details.**

<form onsubmit="return false;">
<div class="input-group mb-3 col-6">
<span class="input-group-text" id="basic-addon1">@</span>
<input type="email" class="form-control" placeholder="Registration Email" aria-label="Email" aria-describedby="basic-addon1" id="registration-email" maxlength="50" required oninput="validate();">
</div>
<div class="col-6">
<button id="btn-submit" class="btn btn-primary" type="submit" onclick="getLab(document.getElementById('registration-email').value)" disabled>Submit</button>
</div>
</form>
<div id="lab" class=".container .text-monospace">
<em>Note you will need a confirmed registration to access the lab.</em>
</div>

## Help 
Having trouble with labs? Send an email to [Mitch Johnson](mailto: mitchj@us.ibm.com) (mitchj@us.ibm.com) and I and/or others will help you sort it out.
