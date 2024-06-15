SETUP PROJECT WITH NEW DEPLOYMENT

- `git clone git@github.com:salmanseif/exam-oms-salman-seif-01.git .`
- `git checkout master_id_2.4.x`
- `composer config repositories.icube-[project-name] git git@github.com:icube-mage/magento2-[project-name].git`
- `composer require icube-mage/magento2-[project-name]:dev-develop`.  
If you create new module and want it to be autoloaded as well, use your own branch. e.g. I 

pushed My new module on branch `fiko-12345678`, then I need to execute this one instead  
`composer require icube-mage/magento2-[project-name]:dev-fiko-12345678`
- Import db and  copy media
- fulldeploy
