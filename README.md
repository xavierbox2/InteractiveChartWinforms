<style>
.column {
  float: left;
  width: 33.33%;
  padding: 5px;
}
</style>

# Interactive Chart for Winforms
Work on progress...

This is an old project motivated to my own need of using charts in many projects.The best control that i have foind is the old Winforms one. 
I am not aware of anything available for UWP and certaibly some commercial solutions appear pricey. 
The WPF style of the charts is not my favourite either. 

However, the Chart control in Winforms isnt interactive out of the box.  

This project is a dll that allows to add Zooming, Panning and Editing to winforms charts with <b> one single line</b> of code

Other functionality such as interpolations and UI manipulation of the charts will be added soon. 
 <pre>
<code>
  public Form1()
        {
            (...)
            
            ChartInteractor = ChartInteractionZoomPanEdit.CreateInstance(chart1);

            (...)
        }
       
</code>
 </pre>
 
 ![alt-text-1](Capture1.PNG"title-1") ![alt-text-2](Capture2.PNG "title-2")
 
 

