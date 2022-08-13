# Wps YII2 Widget Icon
- Contributors: webpagestudio.net
- Tags: icon for yii2
- Stable tag: 1.0.1

## Use
```
<?=Icon::widget([
    'classList' => 'fa fa-cog',
    'href' => 'htts://webpagestudio.com',
    'tooltip'=> Yii::t('app', 'Test text'),
]?>

<?= Icon::widget([
    'name' => 'info',
    'tooltip' => '+1234567890',
    'onclick' => 'copyText(\'+1234567890\')',
]) ?>
```

## Description
Widget create icon

## Installation
- Upload `yii2-icon` to directory with your widget

## Changelog
- 1.0.1
  - add href, refactoring
- 1.0.0
  - first release