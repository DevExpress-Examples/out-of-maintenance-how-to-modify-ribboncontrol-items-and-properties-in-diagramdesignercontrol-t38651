# How to: Modify RibbonControl Items and Properties in DiagramDesignerControl


There are several ways to customize the built-in RibbonControl:<br><strong>1. Use the <a href="https://documentation.devexpress.com/WPF/CustomDocument10587.aspx">RibbonControl's Merging</a> feature.</strong> Create an external RibbonControl with required elements and attach the <a href="https://documentation.devexpress.com/#WPF/DevExpressXpfBarsMergingProperties_ElementMergingBehaviortopic">MergingProperties.ElementMergingBehavior</a> property to DiagramDesignerControl. After performing this, elements form the DiagramDesignerControl's ribbon will be merged with the parent ribbon.<br><strong>2. Customization actions.</strong> Using customization actions, you can create/remove/update bar items. Use the DiagramDesignerControl.Actions property to define customization actions. The <a href="https://documentation.devexpress.com/#CoreLibraries/clsDevExpressDiagramCoreDefaultBarItemNamestopic">DevExpress.Diagram.Core.DefaultBarItemNames</a> class contains default item captions displayed in the diagram's Ribbon.<br><strong>3. Overriding theme styles.</strong> Almost all bar items in DiagramDesignerControl have styles defined as DynamicResource. You can override these styles and set required properties in them. To learn more about modifying our theme resources, refer to <a href="https://www.devexpress.com/Support/Center/p/KA18580">How to modify DX themes in WPF</a>.

<br/>


