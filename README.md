<html lang="en"><head>
  <body>
    <h1>Final Project: Overview</h1>
    <p><strong>Estimated time needed:</strong> 3 hours</p>
    <p>The final project for this course has several steps that you must complete. To give you an overview of the whole project, all the high-level steps are listed below. The project is then divided into several smaller labs that give the detailed instructions for each step. You must complete all the labs to successfully complete the project.</p>
    <h2>Project Breakdown</h2>
    <p><strong>Prework: Sign up for IBM Cloud account and create a Watson Natural language Understanding service</strong></p>
    <ol>
      <li>Create an IBM cloud account if you don't have one already.</li>
      <li>Create an instance of the Natural Language Understanding (NLU) service.</li>
    </ol>
    <p><strong>Part A: Fork the Git repository to have the server and client code you need to start</strong></p>
    <ol>
      <li>Create your own copy of the git repository which has the code you need to build up on.</li>
      <li>Clone the repository into the theia environment</li>
    </ol>
    <p><strong>Part B: npm install the necessary packages</strong></p>
    <ol>
      <li>Change to the React client directory (<em>sentimentanalyzeClient</em>) and install all the packages required in your local environment for the React application to run.</li>
      <li>Change to the express JS server directory (<em>sentimentAnalyzeServer</em>) and install all the packages required in your local environment for the server to run.</li>
    </ol>
    <p><strong>Part C: Install IBM Watson package and set up the .env file</strong></p>
    <ol>
      <li>Install the ibmwatson package in your server and create .env file to add the credentials to point to your Watson NLU credentials, in the <em>sentimentAnalyzeServer</em> directory.</li>
      <li>Make changes in sentimentAnalyzerServer.js to create an instance of NaturalLanguageUnderstanding using the credential from the .env file using dotenv package.</li>
    </ol>
    <p><strong>Part D: Create endpoints to cater to the URL and text input from the React client</strong></p>
    <ol>
      <li>Create four different end points each of which can use the same instance of NLU</li>
      <li>Run the server and the React application to see if the desired output is displayed</li>
      <li>Render the analysis from the server color formatted depending on the sentiment analyzed.</li>
      <li>Render the confidence level of all the emotions in the text or url sent.</li>
    </ol>
 
</body></html>
