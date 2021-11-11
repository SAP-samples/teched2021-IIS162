# Exercise 2 - Document Custom Processes

SAP standard practices are comprehensive and support many important functions of an cooperation. Still, companies are very unique and also have own practices that are not (yet) provided as SAP standard content. 

In this chapter you will document your own process models using SAP Cloud ALM.

## Exercise 2.1 Sub Exercise 1 Description

1. Enter "Process Authoring".
<br> ![](2021-11-11-16-09-47.png)
<br> (1) Click Process Authoring

2.	Create New Solution Process.
<br> ![](2021-11-11-16-10-40.png)
<br> (1) Click "Create"
<br>
<br> ![](2021-11-11-16-21-42.png)
<br> (1) ...
<br> (2) ...
<br> (3) ...
<br> (4) Click "Save".

3. Model Your Solution Value Flow diagram to depcit scope of the process.
<br> ![](2021-11-11-16-53-11.png)
<br> (1) ...
<br> (2) ...
<br> (3) Click "Save".

1. Model Your Solution Process Flow Diagram to depcit the process execution.
<br> ![](2021-11-11-16-56-43.png)
<br> (1) ...
<br> (2) ...
<br>
<br>

## Exercise 2.2 Sub Exercise 2 Description

After completing these steps you will have...

1.	Enter this code.
```abap
DATA(lt_params) = request->get_form_fields(  ).
READ TABLE lt_params REFERENCE INTO DATA(lr_params) WITH KEY name = 'cmd'.
  IF sy-subrc = 0.
    response->set_status( i_code = 200
                     i_reason = 'Everything is fine').
    RETURN.
  ENDIF.

```

2.	Click here.
<br> ![](/exercises/ex2/images/02_02_0010.png)

## Summary

You've now ...

Continue to - [Exercise 3 - Excercise 3 ](../ex3/README.md)
