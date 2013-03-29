Gake
====

Merge of Grunt and Cake.

Gakefile is a simple JSON:

    [
        {
            "description": "Copying a JS lib",
            "command": "cp /my/dev/lib.js /my/prod/js/lib/"
        },
        {
            "description": "Compile Coffee to JS",
            "command": "coffee -c -o /my/prod/js /my/dev/coffee"
        },
        {
            "description": "Crunch it with require.js",
            "command": "r.js -o /my/dev/build.js"
        }
    ]