# Javascript-Password-Generator
Script to generate password with uppercase lowercase number and symbol with JavaScript.

Add to Bookmark bar and enjoy:

javascript:var p="";for(;;){var rnd=Math.floor(Math.random()*128);if(rnd>=33&&rnd<=126){p+=String.fromCharCode(rnd);}if(p.length==16){if(p.match(/(?=.*\d)(?=.*[a-z])(?=.*[A-Z])((?=.*\W)|(?=.*_))^[^ ]+$/g)){break;}else{p="";}}}alert(p);


[EoF]
