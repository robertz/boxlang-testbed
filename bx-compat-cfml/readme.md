# ⚡︎ BoxLang Module: BoxLang Compat Module For CFML

```
|:------------------------------------------------------:|
| ⚡︎ B o x L a n g ⚡︎
| Dynamic : Modular : Productive
|:------------------------------------------------------:|
```

<blockquote>
	Copyright Since 2023 by Ortus Solutions, Corp
	<br>
	<a href="https://www.boxlang.io">www.boxlang.io</a> |
	<a href="https://www.ortussolutions.com">www.ortussolutions.com</a>
</blockquote>

<p>&nbsp;</p>

## Welcome to the BoxLang Compat Module For CFML

This module will allow your ColdFusion (CFML) applications under Adobe or Lucee to run under BoxLang.  This module will provide the necessary compatibility layer to run your applications under BoxLang.

If there are any issues, please report them to the [BoxLang JIRA](https://ortussolutions.atlassian.net/browse/BL/issues) or the [Module Issues](https://github.com/ortus-boxlang/bx-compat-cfml/issues) repository.

## Settings

Here are the available settings for the compat module:

```js
settings = {
    engine = "lucee"
}
```

The valid engines are `adobe` or `lucee`.  By default the engine is `lucee`.  All module settings can be changed via the `boxlang.json` in your configuration.

```json
"modules" : {
    "compat-cfml" : {
        "disabled" : false,
        "settings" : {
            "engine" : "adobe"
        }
    }
}
```

## Server Scope Mimic

Depending on which engine you select an interceptor will be loaded that will seed the `server` scope with the appropriate engine details.

## Contributed BIFs

The compat module will contribute the following built-in functions globally:

* `cacheClear` - Learn more here: https://cfdocs.org/cacheClear
* `cacheCount` - Learn more here: https://cfdocs.org/cacheCount
* `cacheGet` - Learn more here: https://cfdocs.org/cacheGet
* `cacheGetAll` - Learn more here: https://cfdocs.org/cacheGetAll
* `cacheGetAllIds` - Learn more here: https://cfdocs.org/cacheGetAllIds
* `cacheGetAsOptional` - Learn more here: https://cfdocs.org/cacheGetAsOptional
* `cacheGetDefaultCacheName` - Learn more here: https://cfdocs.org/cacheGetDefaultCacheName
* `cacheGetEngineProperties` - Learn more here: https://cfdocs.org/cacheGetEngineProperties
* `cacheGetMetadata` - Learn more here: https://cfdocs.org/cacheGetMetadata
* `cacheGetOrFail` - Learn more here: https://cfdocs.org/cacheGetOrFail
* `cacheGetProperties` - Learn more here: https://cfdocs.org/cacheGetProperties
* `cacheGetSession` - Learn more here: https://cfdocs.org/cacheGetSession
* `cacheIdExists` - Learn more here: https://cfdocs.org/cacheIdExists
* `cachePut` - Learn more here: https://cfdocs.org/cachePut
* `cacheRegionExists` - Learn more here: https://cfdocs.org/cacheRegionExists
* `cacheRegionNew` - Learn more here: https://cfdocs.org/cacheRegionNew
* `cacheRegionRemove` - Learn more here: https://cfdocs.org/cacheRegionRemove
* `cacheRemove` - Learn more here: https://cfdocs.org/cacheRemove
* `cacheRemoveAll` - Learn more here: https://cfdocs.org/cacheRemoveAll
* `cacheSetProperties` - Learn more here: https://cfdocs.org/cacheSetProperties
* `deleteClientVariable` - Learn more here: https://cfdocs.org/deleteClientVariable
* `getClientVariablesList` - Learn more here: https://cfdocs.org/getClientVariablesList
* `getComponentMetadata` - Learn more here: https://cfdocs.org/getComponentMetadata
* `getMetaData` - Learn more here: https://cfdocs.org/getMetaData
* `getVariable` - Learn more here: https://cfdocs.org/getVariable
* `setVariable` - Learn more here: https://cfdocs.org/setVariable
* `systemOutput` - Learn more here: https://cfdocs.org/systemOutput


## Ortus Sponsors

BoxLang is a professional open-source project and it is completely funded by the [community](https://patreon.com/ortussolutions) and [Ortus Solutions, Corp](https://www.ortussolutions.com).  Ortus Patreons get many benefits like a cfcasts account, a FORGEBOX Pro account and so much more.  If you are interested in becoming a sponsor, please visits our patronage page: [https://patreon.com/ortussolutions](https://patreon.com/ortussolutions)

### THE DAILY BREAD

 > "I am the way, and the truth, and the life; no one comes to the Father, but by me (JESUS)" Jn 14:1-12
