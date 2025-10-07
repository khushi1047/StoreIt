
<h1>Store It: File and Media Uploads</h1>
<p>
A modern, secure, and user-friendly cloud storage platform designed to help you store, organize, and share your files effortlessly. With features like seamless file synchronization, robust sharing options, and real-time collaboration tools, this app ensures that your data is always accessible whenever and wherever you need it.
</p> 

<h3>1️⃣ Website Features</h3>

<ul>
    <li>Can upload files, videos, image and misilanious files of any king.</li>
    <li>Uploads upto 2gb with the free account.</li>
    <li>Front end with a high end framework like Next JS</li>
    <li>Back end with highly reliable framework like Node JS, and NextJS's advanced routing system.</li>
    <li>Database and file storage with AppWriteJS</li>
</ul>

<h3>2️⃣ Instructions to run this project.</h3>

<ul>
    <li>Use this url to clone the app: "git clone https://github.com/khushi1047/StoreIt"</li>
    <li>Change the directory to the cloned one: "cd StoreIt"</li>
    <li>Install the needed dependencies and packages: "npm install"</li>
    <li>Create a .env file: "touch .env.local" or use vscode to create it manualy</li>
    <li>Add the following variables to .env.local file: 
        <li>"NEXT_PUBLIC_APPWRITE_ENDPOINT" this will most probably be "https://cloud.appwrite.io/v1".</li>
        <li>"NEXT_PUBLIC_APPWRITE_PROJECT" get this from appwrite's website, this is a secret key.</li>
        <li>"NEXT_PUBLIC_APPWRITE_DATABASE" get this from appwrite's website, this is database secret key.</li>
       <li><b>NEXT_PUBLIC_APPWRITE_USERS_COLLECTION</b> — This is the unique ID of your users collection in Appwrite’s database.</li>
  
  <li><b>NEXT_PUBLIC_APPWRITE_FILES_COLLECTION</b> — This is the ID of the collection where you store image or file metadata.</li>
  
  <li><b>NEXT_PUBLIC_APPWRITE_BUCKET</b> — This is the ID of the Appwrite storage bucket used to upload and retrieve files.</li>
  
  <li><b>NEXT_APPWRITE_KEY</b> — This is your Appwrite API key used to authorize backend requests (keep it secret).</li>

    
    <li>Start the project locally: "npm run dev"</li>
    
</ul>


