# Cómo usar la API

##Consulta un campeón específico:

=== "cURL"
    ```bash
    curl https://api.lolchamps.dev/champs/ashe
    ```

=== "JavaScript"
    ```js
    fetch('https://api.lolchamps.dev/champs/ashe')
      .then(res => res.json())
      .then(data => console.log(data));
    ```

=== "Python"
    ```python
    import requests

    res = requests.get('https://api.lolchamps.dev/champs/ashe')
    print(res.json())
    ```

##Consultar a todos los campeones

=== "cURL"
    ```bash
    curl https://api.lolchamps.dev/api/champions
    ```

=== "JavaScript"
    ```js
    fetch('https://api.lolchamps.dev/api/champions')
      .then(res => res.json())
      .then(data => console.log(data));
    ```

=== "Python"
    ```python
    import requests

    res = requests.get('https://api.lolchamps.dev/api/champions')
    print(res.json())
    ```

##Filtrar campeones por rol o clase

=== "cURL"
    ```bash
    curl "https://api.lolchamps.dev/api/champions?role=mage"
    ```

=== "JavaScript"
    ```js
    fetch('https://api.lolchamps.dev/api/champions?role=mage')
      .then(res => res.json())
      .then(data => console.log(data));
    ```

=== "Python"
    ```python
    import requests

    res = requests.get('https://api.lolchamps.dev/api/champions?role=mage')
    print(res.json())
    ```

!!! warning
    Esta API es de ejemplo. No está afiliada con Riot Games.

[Volver al inicio](../index.md)