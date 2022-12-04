# Hey, I'm Jareer 👋

I'm a software developer from Colombo, Sri Lanka. I create high standard softwares and robust web applications.

<p>
  <a href="https://www.linkedin.com/in/jareer-zeenam/" target="_blank"><img alt="Linkedin" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/jareerzeenam" target="_blank"><img alt="Github" src="https://img.shields.io/badge/GitHub-%2312100E.svg?&style=for-the-badge&logo=Github&logoColor=white" /></a>
  <a href="https://twitter.com/Jareer28" target="_blank"><img alt="Twitter" src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" /></a>
</p>

## Skills

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
            Jquery::class,
            Ajax::class,
            Serverless::class,
            Firebase::class,
            Stripe::class,
            Figma::class,
            PhotoShop::class,
            Illustrator::class,
            Python::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To be a Software Solution Architect.';
    }
}
```