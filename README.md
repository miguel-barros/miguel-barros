<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Miguel-Barros&show_icons=true&theme=cobalt&include_all_commits=true&count_private=false"/><img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Miguel-Barros&layout=compact&langs_count=7&theme=dracula"/>

import firebase from "firebase/app";
import "firebase/auth";
import "firebase/database";
import "firebase/storage";

const firebaseConfig = {
  };

if (!firebase.apps.length) {
  firebase.initializeApp(firebaseConfig);
}

export default firebase;
