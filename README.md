# rest-services-test-automation
A soapUi project to automate rest services testing

1. Install SoapUI
2. Clone/Download repository 
3. Open SoapUI and file-->import project "Assignment-soapui-project.xml"

The TestSuite contains 4 test cases

1. Test Case 1 - Perform an API request to produce a list of all dog breeds.
Performs a rest service call https://dog.ceo/api/breeds/list/all
Assesrtions: Check for token "success" in json response

2. Test Case 2 - Using code, verify “retriever” breed is within the list.
Performs a rest service call https://dog.ceo/api/breeds/list/all
Assesrtions: Check for token "success" in json response
Assesrtions: Check for token "retriever" in json response

3. Test Case 3 - Perform an API request to produce a list of sub-breeds for “retriever”. (Diagram 3)
Performs a rest service call https://dog.ceo/api/breed/retriever/list
Assesrtions: Check for token "success" in json response

4. Test Case 4 - Perform an API request to produce a random image / link for the sub-breed “golden”
Performs a rest service call https://dog.ceo/api/breed/retriever/golden/images/random
Assesrtions: Check for token "success" in json response
Assesrtions: Check for token "retriever-golden" in json response



