I. address of configuration file:
  1.SD root directory ControllerConfig/hmbirdsn.pre
  2.Store the root directory locally ControllerConfig/hmbirdsn.pre
  3.2D prompt background picture can be replaced ControllerConfig/background.png
Note£ºAll of these are fixed formats


II the configuration file format

sn:B0F7   (4-digit MAC number)

overtime:60  (the unit is s)

notification£ºtrue    Or false, true for popup system 2D prompt, false for no popup

The colon and before and after do not contain Spaces


III  The message prompt is sent as an Android broadcast

Action £ºcom.picovr.hmbird.connect.message

Get parameters:


     Get the information directly from the intent,

              The key value is: data
              value:  code :msg

There are three types of Code information:
   
   1.A code value of 11 indicates a search timeout

   2.A code value of 14 indicates a connection timeout

   3 A code value of 10 indicates no configuration file (no 2D interface prompt at this time)

   4.A code value of 1 indicates a successful connection
 



