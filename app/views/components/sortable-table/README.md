Use the sortable table component to let users sort columns in ascending or descending order.

{{ dsExample({
  name: 'sortable-table',
  example: 'default',
  height: 450
}) }}

## When to use this component

Use this component when sorting is needed to help find data within a large table of data. This might be useful in combination with the [filter](/patterns/filter-a-list) pattern.

## How it works

There are 2 ways to use the sortable table component. You can use HTML or, if you are using [Nunjucks](https://mozilla.github.io/nunjucks/) or the [GOV.UK Prototype Kit](https://govuk-prototype-kit.herokuapp.com/), you can use the Nunjucks [table macro](https://design-system.service.gov.uk/components/table/).

The component uses JavaScript to progressively enhance the table component:

{% code %}
  <script>
    new MOJFrontend.SortableTable({
      table: $('table')[0]
    });
  </script>
{% endcode %}

## Research on this component

We need more research. If you have used the sortable table component, get in touch to share your research findings.

## Contribute to this component

You can contribute to this component via the [design system backlog](https://github.com/skillsfundingagency/das-design-system/issues/23)