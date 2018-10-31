1. one
2. time
3. state is defined and set in a class where that information belongs. props is information taken from that state to be passed down to the appropriate components. components that need it.
4. state should be used in a container like component. Within a class where all your date can be delegated to its proper children. props should be used as a tool.
5. constructor should be used when you want to pass that class props from another component
6. <Props data={this.state.allTheStuff}/>
7. this.setState({
    allTheStuff: newArr
  })
