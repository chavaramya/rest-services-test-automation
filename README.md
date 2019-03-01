# rest-services-test-automation
A soapUi project to automate rest services testing

1. Install SoapUI
2. Clone/Download repository 
3. Open SoapUI and file-->import project "Assignment-soapui-project.xml"

The TestSuite contains 4 test cases

1. Test Case 1 - Perform an API request to produce a list of all dog breeds. <br/>
Performs a rest service call https://dog.ceo/api/breeds/list/all <br/>
Assesrtions: Check for token "success" in json response <br/>

2. Test Case 2 - Using code, verify “retriever” breed is within the list. <br/>
Performs a rest service call https://dog.ceo/api/breeds/list/all <br/>
Assesrtions: Check for token "success" in json response <br/>
Assesrtions: Check for token "retriever" in json response <br/>

3. Test Case 3 - Perform an API request to produce a list of sub-breeds for “retriever”. (Diagram 3) <br/>
Performs a rest service call https://dog.ceo/api/breed/retriever/list <br/>
Assesrtions: Check for token "success" in json response <br/>

4. Test Case 4 - Perform an API request to produce a random image / link for the sub-breed “golden” <br/>
Performs a rest service call https://dog.ceo/api/breed/retriever/golden/images/random <br/>
Assesrtions: Check for token "success" in json response <br/>
Assesrtions: Check for token "retriever-golden" in json response <br/>



