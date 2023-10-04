<div class="col-xs-12 col-md-10 col-lg-8 contains-images">

      <h1 class="gap">0x04. Typescript</h1>

  <div data-react-class="tags/Tags" data-react-props="{&quot;tags&quot;:[{&quot;id&quot;:46,&quot;value&quot;:&quot;JavaScript&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;},{&quot;id&quot;:53,&quot;value&quot;:&quot;TypeScript&quot;,&quot;author_id&quot;:null,&quot;created_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;,&quot;updated_at&quot;:&quot;2022-06-16T01:59:38.000Z&quot;}]}" data-react-cache-id="tags/Tags-0"><div class="align-items-center d-flex flex-wrap gap-3 my-2"><span class="label label-primary" style="font-size: 14px;">JavaScript</span><span class="label label-primary" style="font-size: 14px;">TypeScript</span></div></div>

  <div data-react-class="projects/ProjectMetadata" data-react-props="{&quot;metadata&quot;:{&quot;author&quot;:&quot;Johann Kerbrat, Engineering Manager at Uber Works&quot;,&quot;weight&quot;:1,&quot;correction&quot;:{&quot;released&quot;:false,&quot;requires_auto_correction&quot;:false,&quot;requires_manual_correction&quot;:true},&quot;bpi&quot;:{&quot;current&quot;:true,&quot;started&quot;:false,&quot;in_second_deadline&quot;:false,&quot;starts_at&quot;:&quot;2023-10-04T06:00:00.000+03:00&quot;,&quot;ends_at&quot;:&quot;2023-10-05T06:00:00.000+03:00&quot;,&quot;second_deadline_at&quot;:&quot;2023-10-07T06:00:00.000+03:00&quot;}}}" data-react-cache-id="projects/ProjectMetadata-0"><ul class="list-group metadata" id="project-metadata"><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-user fa-fw"></i> By: Johann Kerbrat, Engineering Manager at Uber Works</li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-gear fa-fw"></i> Weight: 1</li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-calendar fa-fw"></i> Project will start <span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2023-10-04 06:00 (GMT+03:00)"><span class="datetime">Oct 4, 2023 6:00 AM</span></span>, must end by <span data-container="body" data-html="false" data-placement="auto top" data-toggle="tooltip" title="" data-original-title="2023-10-05 06:00 (GMT+03:00)"><span class="datetime">Oct 5, 2023 6:00 AM</span></span></li><li class="list-group-item"><i aria-hidden="true" class="fa-solid fa-square-check fa-fw"></i> <strong>Manual QA review must be done</strong> (request it when you are done with the project)</li></ul></div>




    


    <div id="project_id" style="display: none" data-project-id="1228"></div>



      

      

      <div class="panel panel-default" id="project-description">
  <div class="panel-body">
    <p><img src="https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2019/12/baea85b5e9a9fb5c36ec.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&amp;X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20231004%2Fus-east-1%2Fs3%2Faws4_request&amp;X-Amz-Date=20231004T083708Z&amp;X-Amz-Expires=86400&amp;X-Amz-SignedHeaders=host&amp;X-Amz-Signature=52e78729b6baa09d2cefea33b04db0bff656ed1696dfbfc5516395c65c46a3ee" alt="" loading="lazy" style=""></p>

<h2>Resources</h2>

<p><strong>Read or watch</strong>:</p>

<ul>
<li><a href="/rltoken/waTSa9Mguj912pel9On57w" title="TypeScript in 5 minutes" target="_blank">TypeScript in 5 minutes</a></li>
<li><a href="/rltoken/iPO8DlHCGzc1jnojLoP9HA" title="TypeScript documentation" target="_blank">TypeScript documentation</a></li>
</ul>

<h2>Learning Objectives</h2>

<p>At the end of this project, you are expected to be able to <a href="/rltoken/PM-5MDItTT0M8Aaa2QIEyQ" title="explain to anyone" target="_blank">explain to anyone</a>, <strong>without the help of Google</strong>:</p>

<ul>
<li>Basic types in Typescript</li>
<li>Interfaces, Classes, and functions</li>
<li>How to work with the DOM and Typescript</li>
<li>Generic types</li>
<li>How to use namespaces</li>
<li>How to merge declarations</li>
<li>How to use an ambient Namespace to import an external library</li>
<li>Basic nominal typing with Typescript</li>
</ul>

<h2>Requirements</h2>

<ul>
<li>Allowed editors: <code>vi</code>, <code>vim</code>, <code>emacs</code>, <code>Visual Studio Code</code></li>
<li>All your files should end with a new line</li>
<li>All your files will be transpiled on Ubuntu 18.04</li>
<li>Your TS scripts will be checked with <code>jest</code> (version 24.9.* )</li>
<li>A <code>README.md</code> file, at the root of the folder of the project, is mandatory</li>
<li>Your code should use the <code>ts</code> extension when possible</li>
<li>The Typescript compiler should not show any warning or error when compiling your code</li>
</ul>

<h2>Configuration Files</h2>

<p>Please use these files for the following tasks</p>

<h3><code>package.json</code></h3>

<details open="">
<summary>Click to show/hide file contents</summary>
<pre><code>
{
  "name": "typescript_dependencies",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "start-dev": "webpack-dev-server --open",
    "build": "webpack",
    "test": "jest"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "@babel/plugin-proposal-export-default-from": "^7.5.2",
    "@babel/preset-typescript": "^7.7.2",
    "@types/jest": "^24.0.23",
    "@typescript-eslint/eslint-plugin": "^2.4.0",
    "@typescript-eslint/parser": "^2.4.0",
    "clean-webpack-plugin": "^3.0.0",
    "fork-ts-checker-webpack-plugin": "^1.5.1",
    "html-webpack-plugin": "^3.2.0",
    "jest": "^24.9.0",
    "source-map": "^0.7.3",
    "ts-jest": "^24.1.0",
    "ts-loader": "^6.2.0",
    "typescript": "^3.6.4",
    "webpack": "^4.41.2",
    "webpack-cli": "^3.3.9",
    "webpack-dev-server": "^3.8.2"
  }
}
</code>
</pre>
</details>

<h3><code>.eslintrc.js</code></h3>

<details open="">
<summary>Click to show/hide file contents</summary>
<pre><code>
module.exports =  {
  parser:  '@typescript-eslint/parser',
  extends:  [
    'plugin:@typescript-eslint/recommended',  // Uses the recommended rules from @typescript-eslint/eslint-plugin
  ],
  parserOptions:  {
    ecmaVersion:  2018,
    sourceType:  'module',
  },
  rules:  {
  },
};
</code>
</pre>
</details>

<h3><code>tsconfig.json</code></h3>

<details open="">
<summary>Click to show/hide file contents</summary>
<pre><code>
{
  "compilerOptions": {
    "outDir": "./dist/",
    "sourceMap": true,
    "noImplicitAny": true,
    "module": "es6",
    "target": "es5",
    "allowJs": true,
    "moduleResolution": "node",
        "skipLibCheck": true
  }
}
</code>
</pre>
</details>

<h3><code>webpack.config.js</code></h3>

<details open="">
<summary>Click to show/hide file contents</summary>
<pre><code>
const path = require("path");
const HtmlWebpackPlugin = require('html-webpack-plugin');
const { CleanWebpackPlugin } = require('clean-webpack-plugin');
const ForkTsCheckerWebpackPlugin = require('fork-ts-checker-webpack-plugin');

module.exports = {
  entry: "./js/main.ts",
  devtool: "inline-source-map",
  module: {
    rules: [
      {
        test: /\.tsx?$/,
        loader: 'ts-loader',
        options: {
          transpileOnly: true
        }
      }
    ]
  },
  resolve: {
    extensions: [".tsx", ".ts", ".js"]
  },
  devServer: {
    contentBase: "./dist"
  },
  plugins: [
    new ForkTsCheckerWebpackPlugin(),
    new CleanWebpackPlugin(),
    new HtmlWebpackPlugin({
      title: "Development"
    })
  ],
  output: {
    filename: "bundle.js",
    path: path.resolve(__dirname, "dist")
  }
};
</code>
</pre>
</details>

  </div>
</div>


      

      

        
          <h2 class="gap">Tasks</h2>

    <div data-role="task11600" data-position="1" id="task-num-0">
      <div class="panel panel-default task-card " id="task-11600">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      0. Creating an interface for a student
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Copy the following configuration files (provided above) into the <code>task_0</code> directory: <code>package.json</code>, <code>.eslintrc.js</code>, <code>tsconfig.json</code>, <code>webpack.config.js</code></p>

<p>Write your code in the <code>main.ts</code> file:</p>

<ul>
<li>Write an interface named Student that accepts the following elements: <code>firstName(string)</code>, <code>lastName(string)</code>, <code>age(number)</code>, and <code>location(string)</code></li>
<li>Create two students, and create an array named <code>studentsList</code> containing the two variables</li>
<li>Using Vanilla Javascript, render a table and for each elements in the array, append a new row to the table</li>
<li>Each row should contain the first name of the student and the location</li>
</ul>

<p>Requirements:</p>

<ul>
<li>When running, Webpack should return <code>No type errors found</code>.</li>
<li>Every variable should use TypeScript when possible.</li>
</ul>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_0/js/main.ts, task_0/package.json, task_0/.eslintrc.js, task_0/tsconfig.json, task_0/webpack.config.js</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11600">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11600" data-batch-id="62" data-toggle="modal" data-target="#task-11600-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11600-users-done-modal" data-task-id="11600" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "0. Creating an interface for a student"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>




    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11600}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11601" data-position="2" id="task-num-1">
      <div class="panel panel-default task-card " id="task-11601">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      1. Let's build a Teacher interface
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create a directory <code>task_1</code> and copy these configuration files into this folder: <code>package.json</code>, <code>tsconfig.json</code>, <code>webpack.config.js</code></p>

<ul>
<li><code>firstName(string)</code> and <code>lastName(string)</code>. These two attributes should only be modifiable when a Teacher is first initialized</li>
<li><code>fullTimeEmployee(boolean)</code> this attribute should always be defined</li>
<li><code>yearsOfExperience(number)</code> this attribute is optional</li>
<li><code>location(string)</code> this attribute should always be defined</li>
<li>Add the possibility to add any attribute to the Object like <code>contract(boolean)</code> without specifying the name of the attribute</li>
</ul>

<p>Example:</p>

<pre><code>const teacher3: Teacher = {
  firstName: 'John',
  fullTimeEmployee: false,
  lastName: 'Doe',
  location: 'London',
  contract: false,
};

console.log(teacher3);

// should print
// Object
// contract: false
// firstName: "John"
// fullTimeEmployee: false
// lastName: "Doe"
// location: "London"
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_1/js/main.ts, task_1/webpack.config.js, task_1/tsconfig.json, task_1/package.json</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11601">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11601" data-batch-id="62" data-toggle="modal" data-target="#task-11601-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11601-users-done-modal" data-task-id="11601" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "1. Let's build a Teacher interface"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11602" data-position="3" id="task-num-2">
      <div class="panel panel-default task-card " id="task-11602">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      2. Extending the Teacher class
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write an interface named <code>Directors</code> that extends <code>Teacher</code>. It requires an attribute named <code>numberOfReports(number)</code></p>

<p>Example:</p>

<pre><code>const director1: Directors = {
  firstName: 'John',
  lastName: 'Doe',
  location: 'London',
  fullTimeEmployee: true,
  numberOfReports: 17,
};
console.log(director1);

// should print
// Object
// firstName: "John"
// fullTimeEmployee: true
// lastName: "Doe"
// location: "London"
// numberOfReports: 17
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_1/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11602">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11602" data-batch-id="62" data-toggle="modal" data-target="#task-11602-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11602-users-done-modal" data-task-id="11602" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "2. Extending the Teacher class"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11603" data-position="4" id="task-num-3">
      <div class="panel panel-default task-card " id="task-11603">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      3. Printing teachers
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write a function <code>printTeacher</code>:</p>

<ul>
<li>It accepts two arguments <code>firstName</code> and <code>lastName</code></li>
<li>It returns the first letter of the firstName and the full lastName</li>
<li>Example: <code>printTeacher("John", "Doe") -&gt; J. Doe</code></li>
</ul>

<p>Write an interface for the function named <code>printTeacherFunction</code>.</p>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_1/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11603">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11603" data-batch-id="62" data-toggle="modal" data-target="#task-11603-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11603-users-done-modal" data-task-id="11603" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "3. Printing teachers"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11604" data-position="5" id="task-num-4">
      <div class="panel panel-default task-card " id="task-11604">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      4. Writing a class
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write a Class named <code>StudentClass</code>:</p>

<ul>
<li>The constructor accepts <code>firstName(string)</code> and <code>lastName(string)</code> arguments</li>
<li>The class has a method named <code>workOnHomework</code> that return the string <code>Currently working</code></li>
<li>The class has a method named <code>displayName</code>. It returns the firstName of the student</li>
<li>The constructor of the class should be described through an Interface</li>
<li>The class should be described through an Interface</li>
</ul>

<p>Requirements:</p>

<ul>
<li>You can reuse the Webpack configuration from the previous exercise to compile the code.</li>
<li>When running <code>npm run build</code>, no TypeScript error should be displayed.</li>
<li>Every variable should use TypeScript when possible.</li>
</ul>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_1/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11604">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11604" data-batch-id="62" data-toggle="modal" data-target="#task-11604-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11604-users-done-modal" data-task-id="11604" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "4. Writing a class"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11605" data-position="6" id="task-num-5">
      <div class="panel panel-default task-card " id="task-11605">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      5. Advanced types Part 1
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create the <code>DirectorInterface</code> interface with the 3 expected methods:</p>

<ul>
<li><code>workFromHome()</code> returning a string</li>
<li><code>getCoffeeBreak()</code> returning a string</li>
<li><code>workDirectorTasks()</code> returning a string</li>
</ul>

<p>Create the <code>TeacherInterface</code> interface with the 3 expected methods:</p>

<ul>
<li><code>workFromHome()</code> returning a string</li>
<li><code>getCoffeeBreak()</code> returning a string</li>
<li><code>workTeacherTasks()</code> returning a string</li>
</ul>

<p>Create a class <code>Director</code> that will implement <code>DirectorInterface</code></p>

<ul>
<li><code>workFromHome</code> should return the string <code>Working from home</code></li>
<li><code>getToWork</code> should return the string <code>Getting a coffee break</code></li>
<li><code>workDirectorTasks</code> should return the string <code>Getting to director tasks</code></li>
</ul>

<p>Create a class <code>Teacher</code> that will implement <code>TeacherInterface</code></p>

<ul>
<li><code>workFromHome</code> should return the string <code>Cannot work from home</code></li>
<li><code>getCoffeeBreak</code> should return the string <code>Cannot have a break</code></li>
<li><code>workTeacherTasks</code> should return the string <code>Getting to work</code></li>
</ul>

<p>Create a function <code>createEmployee</code> with the following requirements:</p>

<ul>
<li>It can return either a <code>Director</code> or a <code>Teacher</code> instance</li>
<li>It accepts 1 arguments:

<ul>
<li><code>salary</code>(either number or string)</li>
</ul></li>
<li>if <code>salary</code> is a number and less than 500 - It should return a new <code>Teacher</code>. Otherwise it should return a <code>Director</code></li>
</ul>

<p>Expected result:</p>

<pre><code>console.log(createEmployee(200));
Teacher
console.log(createEmployee(1000));
Director
console.log(createEmployee('$500'));
Director
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_2/js/main.ts, task_2/webpack.config.js, task_2/tsconfig.json, task_2/package.json</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11605">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11605" data-batch-id="62" data-toggle="modal" data-target="#task-11605-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11605-users-done-modal" data-task-id="11605" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "5. Advanced types Part 1"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11606" data-position="7" id="task-num-6">
      <div class="panel panel-default task-card " id="task-11606">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      6. Creating functions specific to employees
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write a function <code>isDirector</code>:</p>

<ul>
<li>it accepts <code>employee</code> as an argument</li>
<li>it will be used as a type predicate and if the employee is a director</li>
</ul>

<p>Write a function <code>executeWork</code>:</p>

<ul>
<li>it accepts <code>employee</code> as an argument</li>
<li>if the employee is a Director, it will call <code>workDirectorTasks</code></li>
<li>if the employee is a Teacher, it will call <code>workTeacherTasks</code></li>
</ul>

<p>Expected result:</p>

<pre><code>executeWork(createEmployee(200));
Getting to work
executeWork(createEmployee(1000));
Getting to director tasks
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_2/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11606">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11606" data-batch-id="62" data-toggle="modal" data-target="#task-11606-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11606-users-done-modal" data-task-id="11606" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "6. Creating functions specific to employees"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11607" data-position="8" id="task-num-7">
      <div class="panel panel-default task-card " id="task-11607">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      7. String literal types
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Write a String literal type named <code>Subjects</code> allowing a variable to have the value <code>Math</code> or <code>History</code> only.
Write a function named <code>teachClass</code>:</p>

<ul>
<li>it takes <code>todayClass</code> as an argument</li>
<li>it will return the string <code>Teaching Math</code> if <code>todayClass</code> is <code>Math</code></li>
<li>it will return the string <code>Teaching History</code> if <code>todayClass</code> is <code>History</code></li>
</ul>

<p>Expected result:</p>

<pre><code>teachClass('Math');
Teaching Math
teachClass('History');
Teaching History
</code></pre>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_2/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11607">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11607" data-batch-id="62" data-toggle="modal" data-target="#task-11607-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11607-users-done-modal" data-task-id="11607" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "7. String literal types"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>




    <button class="btn btn-default btn-sm" data-toggle="modal" data-target="#container-specs-modal" data-gtm-custom-event-name="task_sandbox_modal" data-gtm-custom-event-options="{&quot;taskId&quot;:11607}"><i aria-hidden="true" class="fa-solid fa-terminal "></i><span>Get a sandbox</span></button>

</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11608" data-position="9" id="task-num-8">
      <div class="panel panel-default task-card " id="task-11608">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      8. Ambient Namespaces
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create a directory called <code>task_3</code> and copy these configuration files into it: <code>package.json</code>, <code>webpack.config.js</code>, <code>tsconfig.json</code>.</p>

<p>The first part of will require that you build an <code>interface</code> and a <code>type</code>. Inside a file named <code>interface.ts</code>:</p>

<ul>
<li>Create a type <code>RowID</code> and set it equal to <code>number</code></li>
<li>Create an interface <code>RowElement</code> that contains these 3 fields:

<ul>
<li><code>firstName</code>: <code>string</code></li>
<li><code>lastName</code>: <code>string</code></li>
<li><code>age?</code>: <code>number</code></li>
</ul></li>
</ul>

<p>You are building the next part of the application architecture. The goal is to save the entities to a database.
Because of time constraints, you can’t write a connector to the database, and you decided to download a library called <code>crud.js</code>. Copy this file into the <code>task_3/js</code> directory.</p>

<p>Here it is</p>

<pre><code>export function insertRow(row) {
  console.log('Insert row', row);
  return Math.floor(Math.random() * Math.floor(1000));
}

export function deleteRow(rowId) {
  console.log('Delete row id', rowId);
  return;
}

export function updateRow(rowId, row) {
  console.log(`Update row ${rowId}`, row);

  return rowId;
}
</code></pre>

<p>Write an ambient file within <code>task_3/js</code>, named <code>crud.d.ts</code> containing the type declarations for each crud function. At the top of the file import <code>RowID</code> and <code>RowElement</code> from <code>interface.ts</code>.</p>

<p>In <code>main.ts</code></p>

<ul>
<li>At the top of the file create a <a href="/rltoken/91U8IZgcc9cmk216FFy0-Q" title="triple slash directive" target="_blank">triple slash directive</a> that includes all the dependencies from <code>crud.d.ts</code></li>
<li>Import the <code>rowID</code> type and <code>rowElement</code> from <code>interface.ts</code></li>
<li>Import everything from <code>crud.js</code> as <code>CRUD</code></li>
</ul>

<p>Create an object called <code>row</code> with the type <code>RowElement</code> with the fields set to these values:</p>

<ul>
<li><code>firstName</code>: <code>Guillaume</code></li>
<li><code>lastName</code>: <code>Salva</code></li>
</ul>

<p>Create a <code>const</code> variable named <code>newRowID</code> with the type <code>RowID</code> and assign the value the <code>insertRow</code>  command.</p>

<p>Next, create a <code>const</code> variable named <code>updatedRow</code> with the type <code>RowElement</code> and update <code>row</code> with an age field set to <code>23</code></p>

<p>Finally, call the <code>updateRow</code> and <code>deleteRow</code> commands.</p>

<p>Expected result:</p>

<pre><code>const obj = {firstName: "Guillaume", lastName: "Salva"};
CRUD.insertRow(obj)
// Insert row {firstName: "Guillaume", lastName: "Salva"}

const updatedRow: RowElement = { firstName: "Guillaume", lastName: "Salva", age: 23 };
CRUD.updateRow(newRowID, updatedRow);
// Update row 125 {firstName: "Guillaume", lastName: "Salva", age: 23}

CRUD.deleteRow(125);
// Delete row id 125
</code></pre>

<p>Requirements:</p>

<ul>
<li>When running <code>npm run build</code>, no TypeScript error should be displayed.</li>
<li>Every variable should use TypeScript when possible.</li>
<li>The main file and the ambient file should both import the types defined in the interface file.</li>
<li>You can easily test your ambient file by looking at the intellisense of your IDE when using the 3rd party functions.</li>
</ul>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_3/js/main.ts, task_3/js/interface.ts, task_3/js/crud.d.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11608">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11608" data-batch-id="62" data-toggle="modal" data-target="#task-11608-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11608-users-done-modal" data-task-id="11608" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "8. Ambient Namespaces"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11609" data-position="10" id="task-num-9">
      <div class="panel panel-default task-card " id="task-11609">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      9. Namespace &amp; Declaration merging
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create a new directory <code>task_4</code> and copy the above <code>tsconfig.json</code> and put this <code>package.json</code> in there</p>

<pre><code>{
  "name": "task_4",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "build": "webpack",
    "test": "echo \"Error: no test specified\" &amp;&amp; exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "@typescript-eslint/eslint-plugin": "^2.4.0",
    "@typescript-eslint/parser": "^2.4.0",
    "clean-webpack-plugin": "^3.0.0",
    "fork-ts-checker-webpack-plugin": "^1.5.1",
    "html-webpack-plugin": "^3.2.0",
    "ts-loader": "^6.2.0",
    "typescript": "^3.6.4",
    "webpack": "^4.41.2",
    "webpack-cli": "^3.3.9",
    "webpack-dev-server": "^3.8.2"
  }
}
</code></pre>

<p>In <code>task_4/js/subjects</code>:</p>

<ul>
<li><p>Create a file <code>Teacher.ts</code> and write a <code>Teacher</code> interface in a namespace named <code>Subjects</code>.</p>

<ul>
<li>the interface requires <code>firstName</code> and <code>lastName</code> as string</li>
</ul></li>
<li><p>Create a file <code>Subject.ts</code> and write a <code>Subject</code> class in the same namespace named <code>Subjects</code>.</p>

<ul>
<li>the class has one attribute <code>teacher</code> that implements the <code>Teacher</code> interface</li>
<li>the class has one setter method <code>setTeacher</code> that accepts a <code>teacher</code> in argument (and as setter, set the instance attribute <code>teacher</code> with it)</li>
</ul></li>
<li><p>Create a file <code>Cpp.ts</code> and make the following modifications in the same namespace.</p>

<ul>
<li>Using declaration merging, add a new optional attribute <code>experienceTeachingC</code> (number) to the <code>Teacher</code> interface</li>
<li>Create a class <code>Cpp</code> extending from <code>Subject</code></li>
<li>Write a method named <code>getRequirements</code> that will return a string <code>Here is the list of requirements for Cpp</code></li>
<li>Write a method named <code>getAvailableTeacher</code> that will return a string <code>Available Teacher: &lt;first name of teacher&gt;</code> </li>
<li>If the teacher doesn’t have any experience in teaching C, then the method should return a string <code>No available teacher</code></li>
</ul></li>
<li><p>Create a file <code>React.ts</code> and write a <code>React Class</code> in the same namespace.</p>

<ul>
<li>Add a new attribute <code>experienceTeachingReact?</code> (number) to the <code>Teacher</code> interface</li>
<li>In the class, write a method named <code>getRequirements</code> that will return a string <code>Here is the list of requirements for React</code></li>
<li>Write a method named <code>getAvailableTeacher</code> that will return a string <code>Available Teacher: &lt;first name of teacher&gt;</code> </li>
<li>If the teacher doesn’t have any experience in teaching React, then the method should return a string <code>No available teacher</code></li>
</ul></li>
<li><p>Create a file <code>Java.ts</code> and write a <code>Java Class</code> in the same namespace.</p>

<ul>
<li>Add a new attribute <code>experienceTeachingJava?</code> (number) to the <code>Teacher</code> interface</li>
<li>In the class, write a method named <code>getRequirements</code> that will return a string <code>Here is the list of requirements for Java</code></li>
<li>Write a method named <code>getAvailableTeacher</code> that will return a string <code>Available Teacher: &lt;first name of teacher&gt;</code> </li>
<li>If the teacher doesn’t have any experience in teaching Java, then the method should return a string <code>No available teacher</code></li>
</ul></li>
</ul>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_4/package.json, task_4/tsconfig.json, task_4/js/subjects/Cpp.ts, task_4/js/subjects/Java.ts, task_4/js/subjects/React.ts, task_4/js/subjects/Subject.ts, task_4/js/subjects/Teacher.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11609">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11609" data-batch-id="62" data-toggle="modal" data-target="#task-11609-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11609-users-done-modal" data-task-id="11609" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "9. Namespace &amp; Declaration merging"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11610" data-position="11" id="task-num-10">
      <div class="panel panel-default task-card " id="task-11610">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      10. Update task_4/js/main.ts
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <ul>
<li>create and export a constant <code>cpp</code> for Cpp Subjects</li>
<li>create and export a constant <code>java</code> for Java Subjects</li>
<li>create and export a constant <code>react</code> for React Subjects</li>
<li>create and export one Teacher object <code>cTeacher</code> with <code>experienceTeachingC = 10</code></li>
<li>for Cpp subject, log to the console <code>C++</code>, set <code>cTeacher</code> as the teacher, call the two methods <code>getRequirements</code> and <code>getAvailableTeacher</code> and print the strings they return</li>
<li>for Java subject, log to the console <code>Java</code>, set <code>cTeacher</code> as the teacher, call the two methods <code>getRequirements</code> and <code>getAvailableTeacher</code>, and print the strings they return</li>
<li>for React subject, log to the console <code>React</code>, set <code>cTeacher</code> as the teacher, call the two methods <code>getRequirements</code> and <code>getAvailableTeacher</code>, and print the strings they return</li>
</ul>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_4/js/main.ts</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11610">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11610" data-batch-id="62" data-toggle="modal" data-target="#task-11610-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11610-users-done-modal" data-task-id="11610" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "10. Update task_4/js/main.ts"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>
    <div data-role="task11611" data-position="12" id="task-num-11">
      <div class="panel panel-default task-card " id="task-11611">
  <span id="user_id" data-id="194319"></span>

  <div class="panel-heading panel-heading-actions">
    <h3 class="panel-title">
      11. Brand convention &amp; Nominal typing
    </h3>

    <div>
        <span class="label label-info">
          mandatory
        </span>
    </div>
  </div>

  <div class="panel-body">
    <span id="user_id" data-id="194319"></span>

    <!-- Progress vs Score -->

    <!-- Task Body -->
    <p>Create a directory <code>task_5</code> and copy these configuration files into the root of <code>task_5</code>: <code>package.json</code>, <code>tsconfig.json</code>, <code>webpack.config.js</code></p>

<p>Create two interfaces <code>MajorCredits</code> and <code>MinorCredits</code> in <code>task_5/js/main.ts</code>:</p>

<ul>
<li>Each interface defines a number named <code>credits</code></li>
<li>Add a brand property to each interface in order to uniquely identify each of them</li>
</ul>

<p>Create two functions named <code>sumMajorCredits</code> and <code>sumMinorCredits</code> in <code>task_5/js/main.ts</code>:</p>

<ul>
<li>Each function takes two arguments <code>subject1</code> and <code>subject2</code></li>
<li><code>sumMajorCredits</code> returns <code>MajorCredits</code> value and <code>sumMinorCredits</code> returns <code>MinorCredits</code> value</li>
<li>Each function sums the credits of the two subjects</li>
</ul>

  </div>

  <div class="list-group">
    <!-- Task URLs -->

    <!-- Github information -->
      <div class="list-group-item">
        <p><strong>Repo:</strong></p>
        <ul>
          <li>GitHub repository: <code>alx-backend-javascript</code></li>
            <li>Directory: <code>0x04-TypeScript</code></li>
            <li>File: <code>task_5/js/main.ts, task_5/package.json, task_5/webpack.config.js, task_5/tsconfig.json</code></li>
        </ul>
      </div>

    <!-- Self-paced manual review -->
  </div>

  <!-- Panel footer - Controls -->
  <div class="panel-footer">
      <div class="align-items-center d-flex justify-content-between">
        
<div>
    <button class="student_task_done btn btn-default btn-sm no" data-task-id="11611">
      <span class="no"><i aria-hidden="true" class="fa-regular fa-square "></i></span>
      <span class="yes"><i aria-hidden="true" class="fa-regular fa-square-check "></i></span>
      <span class="pending"><i aria-hidden="true" class="fa-solid fa-spinner  fa-spin-pulse"></i></span>
      Done<span class="no pending">?</span><span class="yes">!</span>
    </button>

  <button class="student-task-done-by btn btn-default btn-sm" data-task-id="11611" data-batch-id="62" data-toggle="modal" data-target="#task-11611-users-done-modal">
    Help
  </button>
  <div class="modal fade users-done-modal" id="task-11611-users-done-modal" data-task-id="11611" data-batch-id="62">
    <div class="modal-dialog">
        <div class="modal-content">
        <div class="modal-header">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button>
            <h4 class="modal-title">Learners who are done with "11. Brand convention &amp; Nominal typing"</h4>
        </div>
        <div class="modal-body">
            <div class="list-group">
            </div>
            <div class="spinner">
                <div class="bounce1"></div>
                <div class="bounce2"></div>
                <div class="bounce3"></div>
            </div>
            <div class="error"></div>
        </div>
        </div>
    </div>
</div>


</div>


        <div class="fs-4">
        </div>
      </div>


  </div>
</div>

    </div>




          <div data-react-class="projects/ProjectReadyForReview" data-react-props="{&quot;csrfToken&quot;:&quot;EnXrWZ0BDVUEU1Q2CydvZzXlpxX5h0YPQm4VHSPN49JTmmaLa5gh1QmHcgyjFB-URF-a2hoIMjfHz6p_WfuaNA&quot;,&quot;firstReview&quot;:true,&quot;peerReview&quot;:{&quot;availableReviewersURI&quot;:&quot;/corrections/20603476/available_reviewers.json&quot;,&quot;canReviewPeerDirectly&quot;:true,&quot;correctCorrectionURI&quot;:&quot;https://intranet.alxswe.com/corrections/20603476/correct&quot;,&quot;qaReviewsURI&quot;:&quot;/corrections/to_review&quot;,&quot;readyForReviewURI&quot;:&quot;/corrections/20603476/toggle_ready_for_review.json&quot;,&quot;reviewDeadline&quot;:&quot;2023-10-12T06:00:00.000+03:00&quot;,&quot;synchronousManualReview&quot;:false},&quot;toggled&quot;:false}" data-react-cache-id="projects/ProjectReadyForReview-0"><div class="row gap"><div class="col-md-12"><div class="text-center"><button class="btn btn-lg btn-primary">Ready for a  manual review</button></div></div></div></div>

          <div class="modal fade" id="container-specs-modal"><div class="modal-dialog modal-lg"><div class="modal-content"><div class="modal-header"><button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">×</span></button><h4 class="modal-title">Recommended Sandbox</h4></div><div class="modal-body"><div data-react-class="user_containers/ContainerSpecs" data-react-props="{&quot;containerModelName&quot;:&quot;Sandbox&quot;,&quot;containerSpecs&quot;:[{&quot;available&quot;:true,&quot;description&quot;:&quot;\u003cp\u003eUbuntu 18.04 with Node 12\u003c/p\u003e\n&quot;,&quot;id&quot;:29,&quot;name&quot;:&quot;Ubuntu 18.04 - Node 12&quot;,&quot;online&quot;:true}],&quot;containersLimit&quot;:2,&quot;csrfToken&quot;:&quot;ZWDTiR0WHOhyNaF1V-FF6Dlgh7edG7hIwchF6dkeGmwkj15b648waH_hh0__0jUbSNq6eH6UzHBEafqLoyhjig&quot;,&quot;startStatusURI&quot;:&quot;/user_containers/start_status.json&quot;,&quot;startURI&quot;:&quot;/user_containers/start.json&quot;}" data-react-cache-id="user_containers/ContainerSpecs-0"><div><div class="d-flex gap-4 sandboxes-filters"><a class="btn btn-outline-primary"><i aria-hidden="true" class="fa-solid fa-filter"></i><span class="ml-2">Running only</span></a><div class="align-items-center d-flex" style="position: relative; width: 100%;"><input class="form-control" placeholder="Search for an image ..." type="search" value=""></div></div><div class="mt-3"><h3>1 image<small class="ml-2">(0/2 Sandboxes spawned)</small></h3></div><div class="mt-3"><div class="panel panel-default"><div class="panel-body"><div class="align-items-center d-flex flex-wrap justify-content-between"><div><h3 class="mt-0"><i aria-hidden="true" class="fa-solid fa-terminal text-danger"></i><span class="ml-2">Ubuntu 18.04 - Node 12</span></h3><div class="mt-2 text-muted"><p>Ubuntu 18.04 with Node 12</p>
</div></div><div class="d-flex flex-wrap gap-5"><a class="btn btn-success"><i aria-hidden="true" class="fa-solid fa-play"></i><span class="ml-2">Run</span></a></div></div></div></div></div></div></div></div></div></div></div>

  </div>
