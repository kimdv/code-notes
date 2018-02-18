# Dialog

## Save File
```cs
SaveFileDialog savefile = new SaveFileDialog();
savefile.FileName = "diyECG.jpg";
savefile.Filter = "JPG Files (*.jpg)|*.jpg|All files (*.*)|*.*";
if (savefile.ShowDialog() == DialogResult.OK) { /* do something */ }
```