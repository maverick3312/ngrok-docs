
#### Example Response
```json
{
  "event_subscriptions": [
    {
      "id": "esb_2Ggv0YRvwFkA1FSYdoBhVgsew0x",
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2Ggv0YRvwFkA1FSYdoBhVgsew0x",
      "created_at": "2022-10-26T22:20:18Z",
      "metadata": "{\"environment\": \"staging\"}",
      "description": "ip policy creations",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2Ggv0YRvwFkA1FSYdoBhVgsew0x/sources/ip_policy_created.v0"
        }
      ],
      "destinations": [
        {
          "id": "ed_2Ggv0Vxr6Lr7L8GGoG3dQ9DxQW8",
          "uri": "https://api.ngrok.com/event_destinations/ed_2Ggv0Vxr6Lr7L8GGoG3dQ9DxQW8"
        }
      ]
    }
  ],
  "uri": "https://api.ngrok.com/event_subscriptions",
  "next_page_uri": null
}