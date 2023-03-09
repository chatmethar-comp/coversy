<template>
  <NuxtLayout>
    <NuxtPage></NuxtPage>
  </NuxtLayout>
</template>

<script setup>
  import { initializeApp } from "firebase/app";
  import { getAnalytics } from "firebase/analytics";
onMounted(()=>{
// Import the functions you need from the SDKs you need
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBYtHc7Hg2kgbdLs-9o-GnTAe1qUcSesP8",
  authDomain: "coversy-b1127.firebaseapp.com",
  projectId: "coversy-b1127",
  storageBucket: "coversy-b1127.appspot.com",
  messagingSenderId: "892438388024",
  appId: "1:892438388024:web:f9391af55303a90f98f5cd",
  measurementId: "G-TJ44N27NX6"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);

})

</script>
