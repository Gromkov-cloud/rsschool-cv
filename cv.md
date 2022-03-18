# Vasiliy Gromkov

# My contacts
* Telegram: [v_gromkov](https://t.me/v_gromkov "Описание")
* Email: v.gromkov2014@yandex.ru
* Discord nickname: Vasiliy (@Gromkov-cloud)

# Something about me
20 years old, technical university student, not so long ago I learned about web development, I became interested, now I want to learn more about it.
My strengths? I am responsible.
What is my goal? At the moment I don't have a global goal, now I want to learn more about web development and take a course.

# Skills
* HTML, css(sass)
* Js(basics)
* Webpack
* VS Code, Figma
* Git, GitHub

# Code example
### "Directions Reduction" kata solution from Codewars [Task description](https://www.codewars.com/kata/550f22f4d758534c1100025a "Описание")
```
function dirReduc (arr) {
    const north = 'NORTH', south = 'SOUTH', east = 'EAST', west = 'WEST'
    for (let i = 0; i < arr.length;){
        const delEl = function (direction) {
            if (direction === arr[i + 1]) {
                arr.splice(i, 2)
                i = 0
            } else ++i
        }
        switch (arr[i]){
            case north : delEl('SOUTH')
            break
            case south : delEl('NORTH')
            break
            case east : delEl('WEST')
            break
            case west : delEl('EAST')
            break
        }
    }
    return arr
}
```

# Work experience
I made some simple projects in html and css (*links will be here*), tried to repeat the functionality of excel on javascript (*links will be here*), set up webpack, worked with git and github

# Education
1. HTML&CSS - YouTube and various Internet resources
2. Js - Vladilen Minin's YouTube channel, learn.javascript.ru

# Language
1. ru - native
2. en - beginner