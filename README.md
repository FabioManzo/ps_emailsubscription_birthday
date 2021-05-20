# ps_emailsubscription_birthday
Modified version of ps_emailsubscription to let the customer insert her birthday

1 - insert a column in the ps_emailsubscription table. 
    the column is:
        Name: birthday
        Type: date
        
2 - substitute the module entirely in WEBROOT/modules/ps_emailsubscription with the one provided

3 - substitute WEBROOT/themes/YOUR_THEME/modules/ps_emailsubscription/views/templates/hook/ps_emailsubscription.tpl with the one provided
