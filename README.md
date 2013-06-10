RefreshActionItem (native action bar)
=====================================

A fork of [RefreshActionItem][1] that works with the native action bar instead of with ActionBarSherlock. Use it if your app does not need to maintain Android  2.X compatibility.

To add to your application, follow the instructions [here][1], with the only difference that your Maven dependency should be:


```xml
 <dependency>
     <groupId>com.github.manuelpeinado.refreshactionitem-native</groupId>
     <artifactId>RefreshActionItem</artifactId>
     <version>1.0.3</version>
     <type>apklib</type>
 </dependency>
```

If you don't use Maven, just skip the step in which you add ActionBarSherlock to your library project in Eclipse.


Libraries used
--------------------

* [android-viewbadger][2] by Jeff Gilfelt.

Credits
-------

* Cake launcher icon by [IconEden][3].

Who's using it
--------------
 
*Does your app use RefreshActionItem-Native? If you want to be featured on this list drop me a line.*


Developed By
------------

Manuel Peinado Gallego - <manuel.peinado@gmail.com>

<a href="https://twitter.com/mpg2">
  <img alt="Follow me on Twitter"
       src="https://raw.github.com/ManuelPeinado/NumericPageIndicator/master/art/twitter.png" />
</a>
<a href="https://plus.google.com/106514622630861903655">
  <img alt="Follow me on Twitter"
       src="https://raw.github.com/ManuelPeinado/NumericPageIndicator/master/art/google-plus.png" />
</a>
<a href="http://www.linkedin.com/pub/manuel-peinado-gallego/1b/435/685">
  <img alt="Follow me on Twitter"
       src="https://raw.github.com/ManuelPeinado/NumericPageIndicator/master/art/linkedin.png" />

License
-----------

    Copyright 2013 Manuel Peinado

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.




 [1]: https://github.com/ManuelPeinado/RefreshActionItem
 [2]: https://github.com/jgilfelt/android-viewbadger
 [3]: http://www.iconeden.com
