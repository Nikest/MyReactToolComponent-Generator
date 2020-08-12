# MyComponentGenerator

### Installation

```sh
npm install
sudo npm link
```

### How to use

```sh
yo component
```

###Answers

##### Enter name of the component
Name of the component

##### Enter the HTML tag wrapper
generator will create html tad in React Component render method.
An example:
```sh
render() {
    return (<div></div>)
}
```
'div' is default

##### Add a specific path or directory?
Yeoman will generate templates to directory whitc you enter.
An example (if you create component before and now want create children component):

ParentComponent/[directory of children component name]/
