# Yii2-loki-log-target

Yii2 log target for loki

## Setup

add the log as target
```
 [
    'class'=>\asinfotrack\yii2\log\LokiTarget::class,
    'levels'=>['error','warning','info'],
    'url'=>'URLTOYOURLOKIAPI/loki/api/v1/push',
    'labels'=>[>
        'MyLabel'=>'Something',
        ...
    ],
],
```
