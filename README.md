# uipath-practice-rpa-bots
Various Bots developed using UIPath

#### Best Practices:
- When using Type Into Activity:
  - Set SimulateType to True;
  - If its not working, set SimulateType to False, and set SendWindowMessage to True;
  - If both do not work, set both to False, and carry on with the default given
