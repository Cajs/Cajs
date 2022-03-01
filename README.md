### Hi 👋, I'm Cameron Stephen!
<hr>
<p><em>Lead Web Developer at <a href="https://codeheroes.co.uk">Codeheroes</a>


```php
<?php

namespace Cajs;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Codeheroes',
                'position' => 'Lead Web Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Symfony::class,
            Go::class,
        ];
    }
}
```


<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
