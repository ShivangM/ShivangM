<style>
 #typing-text {
     color: #0BCF04;
     border: solid 1px #A8A8A8;
     font-weight: bold;
     text-align: left;
     font-family: 'Courier New', Courier, monospace;
     overflow: auto;
     background-color: #000000;
     font-size: 25px;
     line-height: 25px;
     padding: 7px;
     height: 110px;
     width: 300px;
     outline: none;
     resize: none;
     box-sizing: border-box;
}
</style>

<div align="center">
<h2> 𝐇𝐞𝐥𝐥𝐨, 𝐟𝐞𝐥𝐥𝐨𝐰 <𝚍𝚎𝚟𝚎𝚕𝚘𝚙𝚎𝚛𝚜/>! <img src="https://github.com/ABSphreak/ABSphreak/blob/master/gifs/Hi.gif" width="30px"></h2>
</div>

<div align="center" width="50">

<textarea id="typing-text" readonly></textarea>

</div>

<div align="center">

Please feel free to clone/fork projects, raise issues and submit PRs if you think something could be better. <br>
Ask me anything <a href="https://github.com/ABSphreak/ABSphreak/issues/new"><b>here</b></a><br>
or <a href="mailto:absphreak@outlook.com"><b>email</b></a> me.

<i>Happy Coding!</i> 😊

</div>

<div align="center">

<img align="center" src="https://github-readme-stats.vercel.app/api?username=ABSphreak&include_all_commits=true&count_private=true&show_icons=true&line_height=20&title_color=7A7ADB&icon_color=2234AE&text_color=D3D3D3&bg_color=0,000000,130F40" alt="ABSphreak's Github Stats">

</br>
</br>
<i>Random dev joke for you! (create your own by clicking here ↓)</i><br>
<a href="https://readme-jokes.vercel.app"><img align="center" src="https://readme-jokes.vercel.app/api?bgColor=%23073b4c&textColor=%2306d6a0&aColor=%2306d6a0&borderColor=%2306d6a0" alt="README Jokes"></a>

---

<i>Follow me around the web:</i><br>

<a href="https://www.linkedin.com/in/absphreak" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://www.instagram.com/absphreak" target="_blank"><img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=flat-square&logo=instagram&logoColor=white" alt="Instagram"></a>
<a href="https://twitter.com/ABSphreak" target="_blank"><img src="https://img.shields.io/badge/Twitter-%231DA1F2.svg?&style=flat-square&logo=twitter&logoColor=white" alt="Twitter"></a>
<a href="https://open.spotify.com/user/0170agi99s5hh187g7mtz245b" target="_blank"><img src="https://img.shields.io/badge/Spotify-%231ED760.svg?&style=flat-square&logo=spotify&logoColor=white" alt="Spotify"></a>
<a href="https://dev.to/ABSphreak" target="_blank"><img src="https://img.shields.io/badge/DEV-%230A0A0A.svg?&style=flat-square&logo=DEV.to&logoColor=white" alt="DEV.to"></a>

</div>

<script>
    (function () {
   var CharacterPos = 0;
   var MsgBuffer = "";
   var TypeDelay = 100; 
   var NxtMsgDelay = 1000;
   var MsgIndex = 0;
   var delay;
   var MsgArray = ["Welcome to \nShivang Mishra's \nGithub Profile!"];

   function StartTyping() {
      var id = document.getElementById("typing-text");
      if (CharacterPos != MsgArray[MsgIndex].length) {
         MsgBuffer  = MsgBuffer + MsgArray[MsgIndex].charAt(CharacterPos);
         id.value = MsgBuffer+"_";
         delay = TypeDelay;
         id.scrollTop = id.scrollHeight; 
      } else {
         delay = NxtMsgDelay;
         MsgBuffer   = "";
         CharacterPos = -1;
         if (MsgIndex!=MsgArray.length-1){
           MsgIndex++;
         }else {
           MsgIndex = 0;
         }
       }
       CharacterPos++;
       setTimeout(StartTyping,delay);
   }
StartTyping();
})();
</script>
