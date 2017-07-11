Normal:
```
const { RaisedButton,FloatingActionButton } = require('material-ui');
const { ContentAdd} = require( 'material-ui/svg-icons');

<div>
  <RaisedButton label='Click me!' onTouchTap={() => setState({isOpen: true})} />
  <FeatureDiscoveryPrompt
    onRequestClose={() => setState({isOpen: false})}
    open={state.isOpen}
    backgroundColor='rgb(0,150,136)'
  >
    <FloatingActionButton  label='Click me!' onTouchTap={() => setState({isOpen: true})}> <ContentAdd /> </FloatingActionButton>
  </FeatureDiscoveryPrompt>
</div>
```