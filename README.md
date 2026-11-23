# Hospital-Management-System
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Hospital Management System - StarUML</title>
  <style>
    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      line-height: 1.6;
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
      color: #1f2328;
    }
    h1, h2, h3 {
      border-bottom: 1px solid #d0d7de;
      padding-bottom: 0.3em;
      margin-top: 24px;
    }
    ul {
      padding-left: 24px;
    }
    li {
      margin: 6px 0;
    }
    code {
      background-color: #f6f8fa;
      padding: 2px 6px;
      border-radius: 4px;
      font-family: Consolas, "Courier New", monospace;
      font-size: 0.92em;
    }
    .img-placeholder {
      border: 2px dashed #8c959f;
      background-color: #f6f8fa;
      color: #57606a;
      text-align: center;
      padding: 30px;
      margin: 16px 0;
      border-radius: 6px;
    }
    hr {
      border: 0;
      border-top: 1px solid #d0d7de;
      margin: 24px 0;
    }
  </style>
</head>
<body>

  <h1>Hospital-Management-System</h1>
  <h1>Reg No: 212225040229</h1>
  <h1>Name: B MARLIYA BANU</h1>
  <h1>Date: 18/11/2026</h1>

  <hr />

  <h1>AIM:</h1>
  <p>To develop the Hospital Management System using StarUML.</p>

  <h1>Problem Statement:</h1>
  <ol>
    <li>Manual patient registration, appointment scheduling, and medical record keeping are time-consuming, error-prone, and inconvenient for patients, doctors, and hospital staff, especially during peak hours.</li>
    <li>Patients often face difficulties such as long waiting queues, unavailability of real-time doctor schedules, and lack of transparency regarding appointment status, lab reports, and billing details.</li>
    <li>Hospital authorities struggle to manage doctor duty rosters, ward and bed availability, pharmacy inventory, and patient records using traditional paper-based systems.</li>
    <li>There is a need for an automated, centralized Hospital Management System that provides real-time access to doctor availability, electronic health records (EHR), lab test reports, and billing status.</li>
    <li>The system should allow users to register patients, search doctors, book or cancel appointments, record diagnoses and prescriptions, and receive confirmations via SMS/email while ensuring secure payment processing.</li>
  </ol>

  <hr />

  <h1>UML DIAGRAMS</h1>

  <h1>USE CASE DIAGRAM</h1>
  <p>A use case diagram is a graphical depiction of a user's possible interactions with a system. The use cases are represented by either circles or ellipses, and the actors are shown as stick figures.</p>
  <p>UML is the modeling toolkit used to build these diagrams. Actors' participation in the system is modeled with an association line connecting the actor and the use case.</p>

  <h2>UML use case diagrams are ideal for:</h2>
  <ul>
    <li>Representing the goals of system-user interactions</li>
    <li>Defining and organizing functional requirements in a system</li>
    <li>Specifying the context and requirements of a system</li>
    <li>Modeling the basic flow of events in a single use case</li>
  </ul>

  <div class="img-placeholder">
    &lt;!-- Paste your StarUML Use Case Diagram image tag here --&gt;<br />
    &lt;img width="1024" height="765" alt="Use Case Diagram" src="YOUR_USE_CASE_IMAGE_URL" /&gt;
  </div>

  <hr />

  <h1>CLASS DIAGRAM</h1>
  <p>The Unified Modeling Language (UML) helps model software systems in various ways. Class diagrams are a type of structure diagram used by software engineers to document static software architecture by describing classes, attributes, methods, and relationships present in the system.</p>

  <h2>Use UML class diagrams to:</h2>
  <ul>
    <li>Better understand the general overview of the schematics of an application</li>
    <li>Visually express specific structural needs of the system across teams</li>
    <li>Define relationships (association, inheritance, aggregation, composition) between core entities such as <code>Patient</code>, <code>Doctor</code>, <code>Appointment</code>, <code>MedicalRecord</code>, <code>Prescription</code>, <code>Bill</code>, and <code>Payment</code></li>
  </ul>

  <div class="img-placeholder">
    &lt;!-- Paste your StarUML Class Diagram image tag here --&gt;<br />
    &lt;img width="1024" height="765" alt="Class Diagram" src="YOUR_CLASS_IMAGE_URL" /&gt;
  </div>

  <hr />

  <h1>COMMUNICATION DIAGRAM:</h1>
  <p>A communication diagram offers similar information to a sequence diagram, but while a sequence diagram emphasizes the time and order of events, a communication diagram emphasizes the structural links and numbered messages exchanged between objects in an application.</p>
  <p>Communication diagrams help engineers and stakeholders visualize how system components (such as <code>Patient</code>, <code>AppointmentUI</code>, <code>AppointmentController</code>, <code>Doctor</code>, <code>Bill</code>, and <code>NotificationService</code>) communicate and collaborate directly.</p>

  <div class="img-placeholder">
    &lt;!-- Paste your StarUML Communication Diagram image tag here --&gt;<br />
    &lt;img width="1024" height="765" alt="Communication Diagram" src="YOUR_COMMUNICATION_IMAGE_URL" /&gt;
  </div>

  <hr />

  <h1>PACKAGE DIAGRAM:</h1>
  <p>Package diagrams are structural diagrams used to show the organization and arrangement of various model elements in the form of packages. A package is a grouping of related UML elements, such as diagrams, documents, classes, or sub-packages, depicted as a file folder arranged hierarchically.</p>
  <p>Package diagrams provide a clear visual organization of the layered architecture within the Hospital Management System (such as <strong>Presentation Layer</strong>, <strong>Application/Service Layer</strong>, <strong>Data Access Layer</strong>, and <strong>External Services</strong>).</p>

  <div class="img-placeholder">
    &lt;!-- Paste your StarUML Package Diagram image tag here --&gt;<br />
    &lt;img width="1024" height="765" alt="Package Diagram" src="YOUR_PACKAGE_IMAGE_URL" /&gt;
  </div>

  <hr />

  <h1>ACTIVITY DIAGRAM:</h1>
  <p>Activity diagrams, along with use case and state machine diagrams, are behavioral diagrams that describe the dynamic workflow and step-by-step operations occurring inside the system.</p>
  <p>Activity diagrams help both business stakeholders and developers understand end-to-end processes such as patient registration, doctor slot checking, consultation, prescription generation, and payment settlement.</p>

  <h2>Activity diagrams present several benefits:</h2>
  <ul>
    <li>Demonstrate the logic and decision branches of a workflow</li>
    <li>Describe the sequential and parallel steps performed in a UML use case</li>
  </ul>

  <div class="img-placeholder">
    &lt;!-- Paste your StarUML Activity Diagram image tag here --&gt;<br />
    &lt;img width="1024" height="765" alt="Activity Diagram" src="YOUR_ACTIVITY_IMAGE_URL" /&gt;
  </div>

  <hr />

  <h1>SEQUENCE DIAGRAM</h1>
  <p>A sequence diagram is a type of interaction diagram that describes how—and in what chronological order—a group of objects works together. These diagrams are used by software developers and business professionals to document requirements or model event scenarios such as booking an appointment and completing online billing.</p>

  <div class="img-placeholder">
    &lt;!-- Paste your StarUML Sequence Diagram image tag here --&gt;<br />
    &lt;img width="1024" height="765" alt="Sequence Diagram" src="YOUR_SEQUENCE_IMAGE_URL" /&gt;
  </div>

  <h1>BENEFITS OF SEQUENCE DIAGRAM</h1>
  <ul>
    <li>Represent the detailed message flow of UML use cases</li>
    <li>Model the logic of a sophisticated procedure, function, or operation</li>
    <li>Visualize how objects and components interact over time to complete a process</li>
    <li>Plan and understand the detailed functionality of an existing or future scenario</li>
  </ul>

  <hr />

  <h1>RESULT</h1>
  <p>Thus the project to develop Hospital Management System was developed using StarUML Software is done successfully.</p>

</body>
</html>
