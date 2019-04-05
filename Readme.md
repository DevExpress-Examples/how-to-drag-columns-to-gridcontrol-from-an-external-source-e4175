<!-- default file list -->
*Files to look at*:

* [DropTargets.cs](./CS/DragDropColumns/DropTargets.cs) (VB: [DropTargets.vb](./VB/DragDropColumns/DropTargets.vb))
* **[MainWindow.xaml](./CS/DragDropColumns/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DragDropColumns/MainWindow.xaml))**
* [MainWindow.xaml.cs](./CS/DragDropColumns/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/DragDropColumns/MainWindow.xaml.vb))
* [MyTableView.cs](./CS/DragDropColumns/MyTableView.cs) (VB: [MyTableView.vb](./VB/DragDropColumns/MyTableView.vb))
<!-- default file list end -->
# How to drag columns to GridControl from an external source


<p>To drag columns from an external source (e.g., ListBox) it's necessary to determine the behavior of the TableView when columns are dropped onto it. To do this, create custom DropTargets and assign them to visual elements by <a href="https://www.devexpress.com/Support/Center/p/KA18580">overriding our theme resources</a>.</p>

<br/>


