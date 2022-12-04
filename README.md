# Hey, I'm Jareer 👋

I'm a software developer from Colombo, Sri Lanka. I create high standard robust web applications and mobile applications APIs.

## Skills
👨‍💻 Programming & Web Tools - HTML, CSS, Sass, PHP, Python, JavaScript ES6, GraphQL.
📦 Frameworks - Laravel, Vue.js, Serverless, Node.js, Bootstrap, Tailwind, jQuery, Ajax.
💾 Databases - MySQL, MongoDB, DynamoDB.
📔 Services & Tools - Git, Bitbucket, AWS, Docker, WordPress, PHPcbf, ESLint, Firebase, Heroku.
🌐 Other Software Applications - Microsoft Office packages, Adobe Photoshop, Illustrator, Figma, Zeplin.


```php
<?php

namespace Jareer;

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

    public function getDailySkills(): array
    {
        return [
            Php::class,
            Laravel::class,
            Vuejs::class,
            JavaScript::class,
            Nodejs::class,
            GraphQl::class,
            MySql::class,
            MongoDB::class,
            Bootstrap::class,
            TailwindCss::class,
            Sass::class,
        ];
    }

    public function getOtherSkills(): array
    {
        return [
            Git::class,
            Docker::class,
            WordPress::class,
            Serverless::class,
            jQuery::class,
            Firebase::class,
            Stripe::class,
            Figma::class,
            AWS::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To be a Software Solution Architect.';
    }
}
```