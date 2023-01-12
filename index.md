<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending this Washington Systems Center(WSC) workshop. 

## Accessing the hands-on lab

Click [here](https://github.com/kenishia/NA-ZCONNEE/blob/main/SSA%20Remote%20Lab%20System%20Connection%20Instructions.pdf) to read the instruction for IBM System access.

All lab instructions for OpenAPI 2 exercises are in the "Exercises for Introducton to z/OS Connect" folder on your remote desktop, or can be downloaded from [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/tree/master/OpenAPI2) to view them locally. 

The lab instructions for OpenAPI3 exercises are in the "Exercices for OpenAPI3" folder on your remote desktop or can be downloaded from [here](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop/tree/master/OpenAPI3) to view them localy.

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
Having trouble with labs? Send an email to [Mitch Johnson] (mailto: mitchj@us.ibm.com) and I and/or others will help you sort it out.
