# Home Assistant Weather Forecast Card
Graph of location temperature and rain forecast

## Installation

1. Copy 'weather-card.js' into 'config/www' folder
1. Add reference to file in 'ui-lovelace.yaml

```yaml
  resources:
    - url: /local/weather-card.js
      type: module
```

### Add as a card to your UI

```yaml
      - type: 'custom:weather-forecast'
        long: 5.691333
        lat: 50.851297
        lineColor: 'rgba(89, 160, 238, 1)'
        fillColor: 'rgba(89, 160, 238, 0.2)'
        update_interval: 30
        icon: 'mdi:weather-rainy'
```

 (update interval is in seconds)

### An example in my own UI as a Picture Element:
