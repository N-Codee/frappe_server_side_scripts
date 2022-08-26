# frappe server side scripts
## 1

    def before_insert(self):
        """
        trigger before Insert the document in the database (as a new document).
        this will not trigger for existing records.
		This will check for user permissions if ignore_permissions flag is false
        """
        pass
 ## 2
    
    def after_insert(self):
        """
        trigger after Insert the document in the database (as a new document).
        this will not trigger for existing records.
        """
        pass
        
## 3
    
    def before_validate(self):
        """
        method should be executed before ignoring validations.
        this will execute for both save and submit
        """
        
## 4
    
    def validate(self):
        """
        this will trigger before_save ----  for save action
        this will trigger before_submit ---- for submit action
        This will check for user permissions if ignore_permissions flag is false
        """
        
## 5
    
    def on_update(self):
        """
        this will trigger when doctype have any chnages
        """
        
## 6
    
    def on_change(self):
        """
        this will trigger if the doctype have any workflow action
        """
    
## 7
    
    def on_submit(self):
        """
        this will trigger only before submit the doctype
        This will check for user permissions if ignore_permissions flag is false
        """
        
## 8
    
    def before_cancel(self):
        """
        this will trigger before canceling a submitted document.
        """
        
        
## 9
    
    def on_cancel(self):
        """
        this will trigger after canceling a submitted document.
        """
        
        
 ## 10
    
    def on_trash(self):
        """
        this will trigger before deleting a document.
        """  
        
## 11
    
    def after_delete(self):
        """
        this will trigger after deleting a document.
        """
           
## 12
    
    def before_update_after_submit(self):
        """
        this will trigger before if value changed in any allow on submit field
        """
        
## 13
    
    def on_update_after_submit(self):
        """
        this will trigger after if value changed in any allow on submit field
        """
        
        
## 14
    
    def before_print(self):
        """
        this will trigger before print preview 
        """
