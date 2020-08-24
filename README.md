<!-- readme cache key: tree-readme:2188350:07c93010a313c998bb0d7c69f54b7d50525ca75e -->
<div id="readme" class="clearfix announce instapaper_body ">
  <span class="name"><span class="mini-icon mini-icon-readme"></span> README</span>
  <div class="plain"><pre># Pale
<a href="itms-services://?action=download-manifest&url=https://github.com/luhoaegona/KGB-Public/blob/master/manifest.plist">Install Test1234</a>

Pale is a simple PHP library that allows a developer to easily convert errors to exceptions without having to worry about the details of changing and restoring error handlers.

## Usage
```php
use Pale;
try {
    Pale\run(function() {
        trigger_error(&quot;this will become an exception&quot;);
    });
} catch(ErrorException $e) {
    var_dump($e);
}
```
</pre></div>
