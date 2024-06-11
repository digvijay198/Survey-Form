# Survey-Form
This is the Survey form created following the instruction of freeCodeCamp
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <link href="styles.css" rel=
    "stylsheet">
    <title>Survey Form</title>
  </head>
  <body>
    <h1 id="title">freeCodeCamp Survey Form</h1>
    <p id="description">Thank you for taking the time to help us improve the platform</p>
    <form id="survey-form">
      <label id="name-label">
        <legend>Name</legend>
        <input id="name" type="text" placeholder="Enter your name" required/>
      </label>
      <label id="email-label">
        <legend>Email</legend>
        <input id="email" type="email"
        placeholder="Enter your email" required/>
      <label id="number-label">
        <legend>Age</legend>
        <input id="number" type="number"
        placeholder="Age" required min="10" max="99"/>
      </label>
<legend>Which options best describe your current role?</legend>
        <select id="dropdown">
          <option>Select Current Role</option>
          <option "0">Student</option>
          <option "1">Full Time Job</option>
          <option "2">Full Time Learner</option>
<option "3">Prefer not to say</option>
<option "4">other</option>
        </select>
      </label>
      <label>
        <legend>Would you recommend freeCodeCamp to a friend?</legend>
        <p>Definitely
        <input type="radio" name="recommendation" value="Definitely" /></p>
     <p>Maybe   <input type="radio" name="recommendation" value="Maybe"/</p>
     <p>Not sure  <input type="radio" name="recommendation" value="Not sure"/></p>
   </label>
        <legend>What is your favorite feature of freeCodeCamp?</legend>
  <select id="dropdown">
     <option>Select an option</option>
    <option"0">Challenges</option>
    <option"1">Projects</option>
    <option"2">Community</option>
    <option"3">Open Source</option>
  </select>
<label>
  <legend class="main">What would you like to see improved? </legend><legend>(Check all that apply)</legend class="sub">
</label>
<div><label>Front-end Projects
<input type="checkbox" value="Front-end Projects"/></label></div>
   <div>  <label>Back-end Projects</label>
<input type="checkbox" value="Back-end Projects"/>
<div><label>Data Visualization
<input type="checkbox" value="Data Visualization"/></label>
<div><label>Challenges
<input type="checkbox" value="Challenges"/></label>
<div><label>Open Source Community
<input type="checkbox" value="Open Source Community"/></label>
<div><label>Gitter help rooms
<input type="checkbox" value="Gitter help rooms"/></label>
<div><label>Videos
<input type="checkbox" value="Videos"/></label>
     <div><label>City Meetups
<input type="checkbox" value="City Meetups"/></label>
<div><label>Wiki<input type="checkbox" value="Wiki"/></label>
<div><label>Forum <input type="checkbox" value="Forum"/></label>
<div><label> Additional courses<input type="checkbox" value="Additional courses"/>
</label>
     <legend>Any comments or suggestions?</legend>
       <textarea></textarea>
       <input type="submit" id="submit"/>
    </form>
  </body>
