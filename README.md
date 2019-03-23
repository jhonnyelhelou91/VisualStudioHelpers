# Visual Studio Helpers

Defines snippets and item templates.

## Getting Started

* Copy the files <br />
`git clone 'https://github.com/jhonnyelhelou91/VisualStudioHelper.git' 'C:\git\VisualStudio'`

###Include Item Templates
* Copy Zipped Item Templates to your visual studio directory<br />
`%USERPROFILE%\Documents\Visual Studio 2017\Templates\Item Templates\Visual C#\`
* Restart Visual Studio <br />

###Include Snippets
* Open Tools > Code Snippets Manager or `Ctrl + K, Ctrl + B`
* Select C# from the dropdown
* Add directory `C:\git\Visual Studio\Snippets`

### Prerequisites

* Visual Studio


### Item Templates

#### Entity Type Configuration
* Add new item in your solution
* Replace configuration name with type name (i.e. Model)
* Include namespace for Model
* Configure Model

### Snippets

####AutoMapper
* You can create a mapping for your model using the keyword `map`
* If audit is enabled, You can create a mapping for your audit using the keyword `auditmap`

####DbSet
* You can create a dbset for your model using the keyword `dbset`
* If audit is enabled, You can create a dbset for your audit using the keyword `auditdbset`
