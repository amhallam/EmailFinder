# EmailFinder by Minelead.io
The best email finder and verifier with real time API provided by https://minelead.io/search/

This repo contains a list of codes in python language that users can see in order to find anyone's profesional email in milliseconds.

This API is real time, it will check if the email exists in Minelead Database as well as searching and verifying inflight all the emails found the it does return them in REST.


more details here : https://minelead.io/docs/


## API Reference

#### Search all emails

```http
  GET https://api.minelead.io/v1/search/?domain=www.example.com&key=yourapikey&max-emails=4
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `key` | `string` | **Required**. Your API key , you get can it by subscribing to Minelead.io |
| `domain` | `string` | **Required**.the domain you would like to extract emails from |
| `max-emails` | `number` | *optional. the max emails returned from a domain |
