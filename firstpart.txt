Assignment3
===========
Answer 1)

   01
Instruction Name:	   move vx,vy
Instruction Description:   Moves the content of vy into vx. Both registers must be in the first 256 register range.
Instruction Example:	   0110 - move v0, v1
                           (Moves v1 into v0.)
02
Instruction Name:	   move/from16 vx,vy
Instruction Description:   Moves the content of vy into vx. vy may be in the 64k register range while vx is one of the first 256 registers.
Instruction Example: 	   0200 1900 - move/from16 v0, v25
                           (Moves v25 into v0.)
03
Instruction Name:          move-result vx
Instruction Description:   Move the result value of the previous method invocation into vx.
Instruction Example:       0A00 - move-result v0
                           (Move the return value of a previous method invocation into v0.)
04
Instruction Name:          move-result-wide vx
Instruction Description:   Move the long/double result value of the previous method invocation into vx,vx+1.
Instruction Example:      0B02 - move-result-wide v2
                           (Move the long/double result value of the previous method invocation into v2,v3.)
	
05
Instruction Name:         move-object vx,vy
Instruction Description:  Moves the object reference from vy to vx.
Instruction Example: 	  0781 - move-object v1, v8
                           (Moves the object reference in v8 to v1.)
