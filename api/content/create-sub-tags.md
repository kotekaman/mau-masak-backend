# create sub tags

{% swagger method="post" path="/v1/users/content/sub_tags" baseUrl="" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="header" name="Authorization" required="true" %}

{% endswagger-parameter %}

{% swagger-response status="200: OK" description="" %}
```javascript
{
    "responses": {
        "code": 200,
        "data": "6197724102304889d352210d",
        "isError": false,
        "message": "success"
    }
}
```
{% endswagger-response %}
{% endswagger %}

### Json Body

{% tabs %}
{% tab title="body" %}
```
{
    "conten_tags_id":"61780c138fcc63ed963c8cf8",
    "name":"sub_asoi"
}
```
{% endtab %}

{% tab title="Second Tab" %}

{% endtab %}
{% endtabs %}

### Example

{% tabs %}
{% tab title="curl" %}
```
curl --location --request POST 'http://localhost:8080/v1/users/content/sub_tags' \
--header 'Authorization: xxxxxx' \
--header 'Content-Type: application/json' \
--data-raw '{
    "conten_tags_id":"61780c138fcc63ed963c8cf8",
    "name":"sub_asoi"
}'
```
{% endtab %}

{% tab title="Second Tab" %}

{% endtab %}
{% endtabs %}
