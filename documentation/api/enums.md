# Enumerators

> Each enum can be imported from `ng-snotify` 


### SnotifyPosition

  - leftTop:`"leftTop"`
  - leftCenter:`"leftCenter"`
  - leftBottom:`"leftBottom"`
  - rightTop:`"rightTop"`
  - rightCenter:`"rightCenter"`
  - rightBottom:`"rightBottom"`
  - centerTop:`"centerTop"`
  - centerCenter:`"centerCenter"`
  - centerBottom:`"centerBottom"`

### SnotifyStyle

  - simple:`"simple"`
  - success:`"success"`
  - error:`"error"`
  - warning:`"warning"`
  - info:`"info"`
  - async:`"async"`
  - confirm:`"confirm"`
  - prompt:`"prompt"`
  
  
###### Example
  ```typescript
  import {SnotifyPosition, SnotifyStyle} from 'ng-snotify';

  snotifyService.create({
    title: 'Example title',
    body: null,
    config: {
      position: SnotifyPosition.rightTop,
      type: SnotifyStyle.info,
    }
  })
  ```
