<!DOCTYPE html>

<html>

<head>
    <meta charset="utf-8">
    <title>Module 4 Solution Starter</title>
    <script>
    (function(window) {
        var speakWord = "Hello";
        var helloSpeaker = function(name) {
            console.log(speakWord + " " + name);
        }

        window.helloSpeaker = helloSpeaker;

    })(window);
    </script>
    <script>
    (function(window) {
        var speakWord = "Good Bye";
        var byeSpeaker = function(name) {
            console.log(speakWord + " " + name);
        }

        window.byeSpeaker = byeSpeaker;

    })(window);
    </script>
    <script>
    (function() {

        var names = ["Yaakov", "John", "Jen", "Jason", "Paul", "Frank", "Larry", "Paula", "Laura", "Jim"];

        for (var i = 0; i < names.length; i++) {
            var firstLetter = names[i].charAt(0).toLowerCase();

            if (firstLetter === 'j') {
                byeSpeaker(names[i]);
            } else {
                helloSpeaker(names[i]);
            }
        }

    })();
    </script>
</head>

<body>
    <h1>Module 4 Solution Starter</h1>
    <p>open console to see the output</p>
</body>

</html>
