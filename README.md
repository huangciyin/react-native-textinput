#react-native-inputtext 
##Platform: ios、android
##example
<Input
	labelText={'邀请码'}
	autoFocus={true}
	keyboardType={'numeric'}
	maxLength={4}
	placeholder={'请输入你的邀请码'}
	onChangeText={(text) => this.setState({invitationCode: text})}
	_onDelTextHandle={() => this.setState({invitationCode: ''})}
	value={this.state.invitationCode}
/>