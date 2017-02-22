<h1>Entities</h1>
<p><b>Developer:</b> A person who can submit a software package to be scanned and request licenses and vulnerabilities results.</p>
<p><b>Manager:</b> A person who can request licenses and vulnerabilities results and create or edit policies.</p>
<h1>Data Stores</h1>
<p><b>NIST Vulnerabilities DB:</b> National Institute of Standards and Technology contains software vulnerability information that allows people send package to check vulnerability information</p>
<p><b>Licenses and Vulnerabilities DB:</b> All of the packages that being checked results needs to be stored in this database and use this organization.</p>
<p><b>Policy DB:</b> The database which contains all the policies for this project.</p>
<h1>Processes</h1>
<p><b>Check Software for OSS Components:</b> This process is to organize the package that being sent from Developer and send them to NIST Vulnerability Database and Scan for package license. </p>
<p><b>Scan for OSS Components: </b>This process is to scan all the packages that has been sent for check licenses availability. </p>
<p><b>Retrieve Software License and Vulnerability Info: </b>This process is to retrieve licenses and vulnerabilities information from licenses and vulnerabilities database. </p>
<p><b>Retrieve Software Policy: </b>retrieve all the policy information from policy database. </p>
<p><b>Create New Policy for Software: </b>this process allows the Manager to create New policy, and send it to  policy database through this process. </p>
<h1>Data Flows</h1>
<p><b>Software Package: </b>Software package information that being sent from developer.</p>
<p><b>Software Package Name:</b> The name of the package that being sent to NIST Vulnerability Database.</p>
<p><b>Vulnerabilities Result:</b> The checked result of the package from NIST Vulnerability Database.</p>
<p><b>License Scan Results:</b> License information results that being sent from Scan for OSS Components.</p>
<p><b>Licenses and Vulnerabilities Request:</b> the packages of  vulnerabilities and Licenses that being requested from Developer or Manager.</p>
<p><b>Licenses and Vulnerabilities Results:</b> The packages of vulnerabilities and Licenses results that being pulled from Licenses and Vulnerabilities Database.</p>
<p><b>Request for current Software Policy: </b> Policy information that being requested that from manager.</p>
<p><b>Software Policy:</b> A Package of policy information that being sent from Policy Database.</p>
<p><b>New Policy for Software:</b> New Policy that is made by manager.</p>
<p><b>Edit of Policy for Software:</b> Policy changes that are made by manager.</p>

