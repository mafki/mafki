## Hi there, I'm mohamed amine fki 👋

## A little more about me..

```php
<?php

namespace MOHAMED_AMINE_FKI;

class AboutMe
{
    public function getBio(): string
    {
        return 'I am a dedicated Software Engineering Student, passionate CTF Player, and skilled Web Developer.';
    }

    public function getExperience(): array
    {
        return [
            'work' => [
                'Freelancer',
                'Software Engineering Intern'
            ],
            'skills' => [
                'Web Development',
                'Cybersecurity',
                'Full Stack Development'
            ]
        ];
    }

    public function getCurrentStatus(): array 
    {
        return [
            'learning' => [
            'Advanced Cybersecurity',
            'MERN Stack Development',
            'Cloud Computing',
            ],
            'seeking' => [
                'I am actively working towards securing a full-stack development position to contribute my skills to a dynamic team.'
            ]
        ];
    }

    public function getFutureGoal(): string
    {
        return 'My ultimate goal is to excel in a full-stack development role, creating innovative solutions and delivering exceptional user experiences.';
    }
}

