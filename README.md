- 👋 Hi, I’m josefine


<!---
Muppets6148/Muppets6148 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<h1> my name is orlando <h1>
 .add(
  'with red background',
  withNotes('Testing the background color for the editable area by setting it to red')(() => ({
    component: ContentEditableComponent,
    props: {
      styles: { 'background-color': 'red', 'color': '#fff', 'padding': '20px' },
      ngModel: 'The red content goes here',
      ngModelChange: action('ngModelChange')
    }
  }))
 )


