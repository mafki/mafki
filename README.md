<?php

namespace FKI MOHAMED AMINE;

class About extends Me
{
    public function getBio(): string
    {
        return 'I am Software Engineering Student, CTF Player and a Web Developer.';
    }

    public function getMore(): array
    {
        return [
            'work' => [
                'Freelancer'
            ],
            'education' => [
                'Business Computing',
                'Software Engineering'
            ]
        ];
    }

    public function getCurrentState(): array 
    {
        return [
            'learning' => [
                'Hardware',
                'DevOps and DevSecOps'
            ],
            'looking_for' => [
                'Part Time jobs in Web Developement'
            ]
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
