<template>
  <md-card>
    <md-card-header :data-background-color="dataBackgroundColor">
      <h4 class="title">
        Summary of Skills
      </h4>
      <!-- <p class="category">Complete your profile</p> -->
    </md-card-header>

    <md-card-content>
      <div class="md-layout">
        <div class="md-layout-item md-small-size-100 md-size-33">
          <h5>Languages</h5>
          <p class="category">
            C/C++, Java, Python, SQL, JavaScript, Ruby, HTML/CSS, Verilog
          </p>
        </div>
        <div class="md-layout-item md-small-size-100 md-size-66">
          <h5>Tools/Frameworks</h5>
          <p class="category">
            ReactJS, AngularJS, VueJS, ExpressJS, NodeJS, Typescript, PeerJS, MongoDB, PostgreSQL, MySQL, DBeaver, Socket.io, WebRTC, Stream API, Rapid API, Jenkins, Postman, Jira, Bootstrap 3/4, Material-UI, Git, Alan AI
          </p>
        </div>
        <div class="md-layout-item md-small-size-100 md-size-33">
          <h5>Other Skills</h5>
          <p class="category">
            <ul>
              <li>Problem-Solver</li>
              <li>Quick Self-Learner</li>
              <li>Meet deadlines</li>
              <li>Effective Communication</li>
              <li>Hard Worker</li>
              <li>Time Management</li>
            </ul>
          </p>
        </div>
        <div class="md-layout-item md-small-size-100 md-size-66">
          <h5>Certifications</h5>
          <p class="category">
            <ul>
              <!-- <li>CBSE Certificate of Merit for Physics - Awarded to top 0.1% of candidates passing that subject</li> -->
              <li>TypeScript Fundamentals - Coursera</li>
              <li>CSS Certification - HackerRank</li>
              <li>Game Development - Codecademy</li>
              <li>Tosca Automation Specialist Level 1 - Tricentis</li>
              <li>Tosca Automation Specialist Level 2 - Tricentis</li>
            </ul>
          </p>
        </div>
        <!-- <div class="md-layout-item md-small-size-100 md-size-50">
            <md-field>
              <label>Last Name</label>
              <md-input v-model="lastname" type="text"></md-input>
            </md-field>
          </div> -->
        <!-- <div class="md-layout-item md-small-size-100 md-size-100">
            <md-field>
              <label>Adress</label>
              <md-input v-model="address" type="text"></md-input>
            </md-field>
          </div>
          <div class="md-layout-item md-small-size-100 md-size-33">
            <md-field>
              <label>City</label>
              <md-input v-model="city" type="text"></md-input>
            </md-field>
          </div>
          <div class="md-layout-item md-small-size-100 md-size-33">
            <md-field>
              <label>Country</label>
              <md-input v-model="country" type="text"></md-input>
            </md-field>
          </div> -->
        <!-- <div class="md-layout-item md-small-size-100 md-size-33">
            <md-field>
              <label>Postal Code</label>
              <md-input v-model="code" type="number"></md-input>
            </md-field>
          </div>
          <div class="md-layout-item md-size-100">
            <md-field maxlength="5">
              <label>About Me</label>
              <md-textarea v-model="aboutme"></md-textarea>
            </md-field>
          </div>
          <div class="md-layout-item md-size-100 text-right">
            <md-button class="md-raised md-success">Update Profile</md-button>
          </div> -->
      </div>
    </md-card-content>
  </md-card>
</template>
<script>
export default {
  name: "EditProfileForm",
  props: {
    dataBackgroundColor: {
      type: String,
      default: ""
    }
  },
  data() {
    return {
    };
  }
};
</script>
<style></style>
