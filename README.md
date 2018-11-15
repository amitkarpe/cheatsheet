

# cheatsheet

In both HTML and Flutter, child elements or widgets are anchored at
the top left, by default.

<div class="lefthighlight">
{% prettify css %}
<div class="greybox">
    Lorem ipsum
</div>

.greybox {
      background-color: #e0e0e0; /* grey 300 */
      width: 320px;
      height: 240px;
[[highlight]]      font: 900 24px Georgia;[[/highlight]]
    }
{% endprettify %}
</div>
<div class="righthighlight">
{% prettify dart %}
  var container = Container( // grey box
    child: Text(
      "Lorem ipsum",
      style: [[highlight]]TextStyle(
        fontSize: 24.0
        fontWeight: FontWeight.w900,
        fontFamily: "Georgia",
      ),[[/highlight]]
    ),
    width: 320.0,
    height: 240.0,
    color: Colors.grey[300],
  );
{% endprettify %}
</div>


```
def what?
  42
end
```
{: .language-ruby}


{{ 'Use "Jekyll" --- the static generator...' | smartify }}

{{ page.title | smartify }}

A simple paragraph with an ID attribute.
{: #para-one}

> A blockquote with a title
{:title="The blockquote title"}
{: #myid}

* {:.cls} This item has the class "cls"

{:.ruby}
    Some code here
