# config.xml

Main configuration for the game.

## Properties

### `config`

- `closeTime`
  Controls when the game is closed, in hours and minutes format (e.g. 20:30).
- `openTime`
  Controls when the game is available to be played in hours and minutes format (e.g. 10:15).

#### Notes

- Both properties `closeTime` and `openTime` control the times when players can or cannot play the game.

  For example, if users are expected to play from 10:00 a.m to 16:30 (six and a half hours), the config would be:

  ```xml
  <?xml version="1.0" encoding="UTF-8" ?>
  <config>
      <openTime>10:00</openTime>
	    <closeTime>16:30</closeTime>
  </config>
  ```
