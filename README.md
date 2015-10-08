# bootstrap-tooltip.js
bootstrap，form表单提交tooltip-验证-引导-工具提示

#jQuery-Validation-Bootstrap-tooltip
扩展 jQuery 验证插件错误标签替换工具提示

#Requirements

- [jQuery](http://jquery.com/)
- Bootstrap(http://v3.bootcss.com/)
- jQuery Validation(http://jqueryvalidation.org/)


#Usage

工具提示选项给出了通过元数据属性或对象设置期间验证初始化
example :
### HTML

    $("#theform").validate({
        rules: {
           thefield: { digits:true, required: true }
        },
        tooltip_options: {
           thefield: { placement: 'left' }
        }
     });

#Demonstrate
![Alt text](/path/to/img.jpg)
