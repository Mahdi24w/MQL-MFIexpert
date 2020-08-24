# MQL-MFIexpert
Expert Advisor based on MFI indicator

capable of: buys, sells, martingle

what I learned: using custom function instead of rewriting everything in OnTick(). 


Version:
v1.00

inputs: buy & sell start and end area - MFI Accepted Curve - Lotsizes and pip differences for martingle

entry conditions: when the MFI reaches the user-inputted start.

management: up to 8 position martingle with the specified user-inputted lot sizes and pip diffs

exit conditon: when the MFI reaches the user-inputted end.
