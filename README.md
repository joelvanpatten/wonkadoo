This is the wonkadoo.  Father of the whackadoo and son of the funkadoo.


See here for adding the repo to packagist so it can be "required" by composer.json
 - https://knpuniversity.com/screencast/question-answer-day/create-composer-package
Or here for using a private repo with Satis
 - https://laravelista.com/satis-composer-repository-for-your-private-packages/


composer create-project vendor/name path --repository-url=http://repo.yourcomposerrepo.com

composer create-project joelvanpatten/wonkadoo ./wp-content/plugins/ --repository-url=https://github.com/joelvanpatten/wonkadoo



Installation Instructions
===============================
Add this to your composer.json file

```json
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/joelvanpatten/wonkadoo"
    }
],

...

"require": {
    "joelvanpatten/wonkadoo": "dev-master"
},


```
