# Portfolio
<html>
<head>
<title>
home page
</title>
</head>
<body bgcolor="purple" text="BLACK">
<div align="center">HELLO PEOPLE</div>
<br>MY HOBBY
<p>reading
<p>travel
<swimming
<Photography
<font size="60" color"BLACK">html</font>
<br><b><i><u>web develop</u></i></b> 

</body>
class HelloPeople extends React.Component {
  render() {
    return (
      <div>
        Hello {this.props.name}
      </div>
    );
  }
}

ReactDOM.render(
  <Hellopeople name="Taylor" />,
  mountNode
);
