
# Form.AfterInsert Property (Access)

Returns or sets a  **String** indicating which macro, event procedure, or user-defined function runs when the ** [AfterInsert](07140c13-ce7c-91f2-7451-d7f834653ef2.md)**event occurs. Read/write.


## Syntax

 _expression_. **AfterInsert**

 _expression_A variable that represents a  **Form** object.


## Remarks

Valid values for this property are "macroname" where macroname is the name of macro, "[Event Procedure]" which indicates the event procedure associated with the **BeforeInsert** event for the specified object, or "=functionname()" wherefunctionname is the name of a user-defined function.


## Example

The following example specifies that when the  **AfterInsert** event occurs on the first form of the current project, the associated event procedure should run.


```
Forms(0).After Insert = "[Event Procedure]" 

```


## See also


#### Concepts


 [Form Object](72ef9219-142b-b690-b696-3eba9a5d4522.md)
#### Other resources


 [Form Object Members](e1976b58-28ca-8f76-cdf3-6732cb06ce6c.md)
