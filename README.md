# frappe server side scripts
## 1

    def before_insert(self):
        """
        trigger before the first insert into database table
        this will not trigger for existing records.
        """
        pass
 ## 2
    
    def after_insert(self):
        """
        trigger after the first insert into database table
        this will not trigger for existing records.
        """
        pass
