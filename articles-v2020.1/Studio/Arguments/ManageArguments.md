# 管理参数 
参数用于将数据从项目传递到另一个项目。在全局意义上，它们类似于变量，因为它们动态地存储数据并将其传递。变量在组件之间传递数据，而参数在自动化工作流程之间传递数据。因此，它们使您能够一次又一次地重用自动化工作流程。 

天匠智能编辑器支持大量的参数类型，这些参数类型与变量类型一致。因此，您可以创建字符串，布尔值，对象，数组或 DataTable 参数，也可以浏览 .Net 类型，和在变量的情况下一样。 

此外，参数具有特定的传递方向（输入，输出，输入/输出，属性），告诉应用程序存储在其中的信息应该传递到哪里。

## 创建参数 
>注意： 
> 
>参数名称应在驼峰上用一个前缀，说明参数传递的方向。 
> 
>如 in_DefaultTimeout，in_FileName，out_TextResult，io_RetryNumber。

要创建新参数： 
1、在“设计窗口”中，单击“参数”。将显示参数面板。  
* 2、单击“创建参数”行。将显示具有默认字段值的新参数。 
  
>注意：   
> 
>默认情况下，所有参数都是输入方向的字符串 (String) 类型。  

## 删除参数 
1、在参数面板中，选择一个参数并按 Delete 。 
2、在参数面板中，选中一个参数并右击，在上下文菜单中点击“删除”选项。 
  
## 参数的使用 
在自动化流程中为某一元素创建参数并将该自动化流程上传至天匠智能控制台后，可为其创建参数集，使自动化流程多样化。如此，便可以选择不同的参数对自动化流程进行测试。 
