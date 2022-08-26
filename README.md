# frappe server side scripts

    def before_insert(self):
        """
        trigger before the first insert into database table
        this will not trigger for existing records.
        """
        pass
    
    def after_insert(self):
        """
        trigger after the first insert into database table
        this will not trigger for existing records.
        """
        pass
