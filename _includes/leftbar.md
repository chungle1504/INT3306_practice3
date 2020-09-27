{% if include.category == "Javascript" %}

<div class="left-bar">
  <ul>
    <li class="nav-bar-item">
      <a {% if include.site contains "Syntax" %} class="active" {% endif %} href="./syntax.html">Syntax</a>
    </li>
    <li>
      <a {% if include.site contains "Variables" %} class="active" {% endif %} href="./variables.html">Variables</a>
    </li>
    <li>
      <a {% if include.site contains "Operators" %} class="active" {% endif %} href="./operators.html">Operators</a>
    </li>
    <li>
      <a {% if include.site contains "Data types" %} class="active" {% endif %} href="./data_types.html">Data types</a>
    </li>
    <li>
      <a {% if include.site contains "Functions" %} class="active" {% endif %} href="./functions.html">Functions</a>
    </li>
    <li>
      <a {% if include.site contains "Objects" %} class="active" {% endif %} href="./objects.html">Objects</a>
    </li>
    <li>
      <a {% if include.site contains "Events" %} class="active" {% endif %} href="./events.html">Events</a>
    </li>
    <li>
      <a {% if include.site contains "Conditions" %} class="active" {% endif %} href="./conditions.html">Conditions</a>
    </li>
    <li>
      <a {% if include.site contains "Loops" %} class="active" {% endif %} href="./loops.html">Loops</a>
    </li>
    <li>
      <a {% if include.site contains "RegExp" %} class="active" {% endif %} href="./regexp.html">RegExp</a>
    </li>
  </ul>
</div>

{% endif %}

{% if include.category == "CSS" %}

<div class="left-bar">
  <ul>
   <li class="nav-bar-item">
      <a {% if include.site contains "Syntax" %} class="active" {% endif %} href="./syntax.html">Syntax</a>
    </li>
    <li>
      <a {% if include.site contains "Selectors" %} class="active" {% endif %} href="./selectors.html">Selectors</a>
    </li>
    <li>
      <a {% if include.site contains "Colors" %} class="active" {% endif %} href="./colors.html">Colors</a>
    </li>
    <li>
      <a {% if include.site contains "Backgrounds" %} class="active" {% endif %} href="./backgrounds.html">Backgrounds</a>
    </li>
    <li>
      <a {% if include.site contains "Margins" %} class="active" {% endif %} href="./margins.html">Margins</a>
    </li>
    <li>
      <a {% if include.site contains "Sizes" %} class="active" {% endif %} href="./sizes.html">Sizes</a>
    </li>
    <li>
      <a {% if include.site contains "Texts" %} class="active" {% endif %} href="./texts.html">Texts</a>
    </li>
    <li>
      <a {% if include.site contains "Fonts" %} class="active" {% endif %} href="./fonts.html">Fonts</a>
    </li>
  </ul>
</div>

{% endif %}

{% if include.category == "HTML" %}

<div class="left-bar">
  <ul>
    <li class="nav-bar-item">
      <a {% if include.site contains "Headings" %} class="active" {% endif %} href="./headings.html">Headings</a>
    </li>
    <li>
      <a {% if include.site contains "Paragraphs" %} class="active" {% endif %} href="./paragraphs.html">Paragraphs</a>
    </li>
    <li>
      <a {% if include.site contains "Links" %} class="active" {% endif %} href="./links.html">Links</a>
    </li>
    <li>
      <a {% if include.site contains "Images" %} class="active" {% endif %} href="./images.html">Images</a>
    </li>
    <li>
      <a {% if include.site contains "Lists" %} class="active" {% endif %} href="./lists.html">Lists</a>
    </li>
    <li>
      <a {% if include.site contains "tables" %} class="active" {% endif %} href="./tables.html">tables</a>
    </li>
    <li>
      <a {% if include.site contains "forms" %} class="active" {% endif %} href="./forms.html">forms</a>
    </li>
  </ul>
</div>

{% endif %}



