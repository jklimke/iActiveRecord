## ActiveRecord without CoreData.
### Only SQLite.
### Only HardCore.

You do not need to create tables manually - just describe your ActiveRecord and enjoy!!!

    #import <ActiveRecord/ActiveRecord.h>

    @interface User : ActiveRecord

    @property (nonatomic, retain) NSString *name;

    @end
    

### Check [Wiki](https://github.com/AlexDenisov/iActiveRecord/wiki) to see features and HowTo!