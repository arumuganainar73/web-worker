STEP 1 :
	CREATE FIREBASE CONSOLE PROJECT

Step 2 :

copy paste the script from console.firebase in relevant pjt
	  ////////////////////////// sample here //////////////////////
<script src="https://www.gstatic.com/firebasejs/5.8.2/firebase.js"></script>
<script>
  // Initialize Firebase
  var config = {
    apiKey: "AIzaSyCf608CfGZLX7Qadl18Rnu3uElrshdYBUI",
    authDomain: "web-worker-ff594.firebaseapp.com",
    databaseURL: "https://web-worker-ff594.firebaseio.com",
    projectId: "web-worker-ff594",
    storageBucket: "web-worker-ff594.appspot.com",
    messagingSenderId: "192762019347"
  };
  firebase.initializeApp(config);
</script>
//////////////////// sample ends here

Step 3 :
firebase login

Step 4 : (try doing step 5 directly)
firebase use --add 

then select the project that has been already created in firebase console

Step 5: 
firebase use <<project name>>

STEP 6:
firebase init
	are you want to proceed - Y
	select (*)hosting: configure and deploy firebase Hosting sited -- USING SPACE BAR
	Make public as default direcory   - ENTER
STEP 7:
	To host alone :

firebase deploy -m "first-deployment" --only hosting


Complete deployment including store , funct and host :

firebase deploy -m "first-deployment"



Deployed in : 
https://sw-demo-236f8.firebaseapp.com/