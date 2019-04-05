<!-- default file list -->
*Files to look at*:

* [ListBoxDropTarget.cs](./CS/DragDropColumns/ListBoxDropTarget/ListBoxDropTarget.cs) (VB: [ListBoxDropTargetFactory.vb](./VB/DragDropColumns/ListBoxDropTarget/ListBoxDropTargetFactory.vb))
* [ListBoxDropTargetFactory.cs](./CS/DragDropColumns/ListBoxDropTarget/ListBoxDropTargetFactory.cs) (VB: [ListBoxDropTargetFactory.vb](./VB/DragDropColumns/ListBoxDropTarget/ListBoxDropTargetFactory.vb))
* [MainWindow.xaml](./CS/DragDropColumns/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/DragDropColumns/MainWindow.xaml))
* [MainWindow.xaml.cs](./CS/DragDropColumns/MainWindow.xaml.cs) (VB: [MainWindow.xaml.vb](./VB/DragDropColumns/MainWindow.xaml.vb))
* [MyColumnChooserDropTarget.cs](./CS/DragDropColumns/MyColumnChooserDropTarget/MyColumnChooserDropTarget.cs) (VB: [MyColumnChooserDropTarget.vb](./VB/DragDropColumns/MyColumnChooserDropTarget/MyColumnChooserDropTarget.vb))
* [MyColumnChooserDropTargetFactory.cs](./CS/DragDropColumns/MyColumnChooserDropTarget/MyColumnChooserDropTargetFactory.cs) (VB: [MyColumnChooserDropTargetFactory.vb](./VB/DragDropColumns/MyColumnChooserDropTarget/MyColumnChooserDropTargetFactory.vb))
* [MyFitColumnHeaderDropTarget.cs](./CS/DragDropColumns/MyFitColumnHeaderDropTargetFactory/MyFitColumnHeaderDropTarget.cs) (VB: [MyFitColumnHeaderDropTargetFactory.vb](./VB/DragDropColumns/MyFitColumnHeaderDropTargetFactory/MyFitColumnHeaderDropTargetFactory.vb))
* [MyFitColumnHeaderDropTargetFactory.cs](./CS/DragDropColumns/MyFitColumnHeaderDropTargetFactory/MyFitColumnHeaderDropTargetFactory.cs) (VB: [MyFitColumnHeaderDropTargetFactory.vb](./VB/DragDropColumns/MyFitColumnHeaderDropTargetFactory/MyFitColumnHeaderDropTargetFactory.vb))
* [MyFixedNoneColumnHeaderDropTargetFactory.cs](./CS/DragDropColumns/MyFixedNoneDropTarget/MyFixedNoneColumnHeaderDropTargetFactory.cs) (VB: [MyFixedNoneColumnHeaderDropTargetFactory.vb](./VB/DragDropColumns/MyFixedNoneDropTarget/MyFixedNoneColumnHeaderDropTargetFactory.vb))
* [MyFixedNoneDropTarget.cs](./CS/DragDropColumns/MyFixedNoneDropTarget/MyFixedNoneDropTarget.cs) (VB: [MyFixedNoneDropTarget.vb](./VB/DragDropColumns/MyFixedNoneDropTarget/MyFixedNoneDropTarget.vb))
* [MyGridColumnHeader.cs](./CS/DragDropColumns/MyGridColumnHeader.cs) (VB: [MyGridColumnHeader.vb](./VB/DragDropColumns/MyGridColumnHeader.vb))
* [MyRemoveColumnDropTarget.cs](./CS/DragDropColumns/MyRemoveColumnDropTarget.cs) (VB: [MyRemoveColumnDropTarget.vb](./VB/DragDropColumns/MyRemoveColumnDropTarget.vb))
* [MyTableView.cs](./CS/DragDropColumns/MyTableView/MyTableView.cs) (VB: [MyTableView.vb](./VB/DragDropColumns/MyTableView/MyTableView.vb))
<!-- default file list end -->
# How to drag columns to GridControl from an external source


<p>To drag columns from an external source (e.g., ListBox) it's necessary to determine the behavior of the TableView when columns are dropped onto it. To do this, create custom DropTargets and assign them to visual elements by <a href="https://www.devexpress.com/Support/Center/p/KA18580">overriding our theme resources</a>.</p>

<br/>


