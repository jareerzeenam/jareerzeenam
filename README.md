# Hey, I'm Jareer 👋

I'm a software developer from Colombo, Sri Lanka. I create high standard robust web applications and mobile applications APIs.

## Skills
👨‍💻 Programming & Web Tools - HTML, CSS, Sass, PHP, Python, JavaScript ES6, GraphQL.
📦 Frameworks - Laravel, Vue.js, Serverless, Node.js, Bootstrap, Tailwind, jQuery, Ajax.
💾 Databases - MySQL, MongoDB, DynamoDB.
📔 Services & Tools - Git, Bitbucket, AWS, Docker, WordPress, PHPcbf, ESLint, Firebase, Heroku.
🌐 Other Software Applications - Microsoft Office packages, Adobe Photoshop, Illustrator, Figma, Zeplin.


```
<?php

namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Adventus.io',
                'position' => 'Full Stack Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```