# Project

This react hooks tracks that user is online or offline. You can directly use in your function component and can get the online status of user in boolean form.

## Getting Started

const StatusIndicator = () => {
const isOnline = useNavigatorOnLine();

return <span>You are {isOnline ? "online" : "offline"}.</span>;
};

ReactDOM.render(<StatusIndicator />, document.getElementById("root"));

### Prerequisites

Works with React 16.8.0 and above.

### Installing

\$ npm install react-isonline-hook --save

## Versioning

1.0.0

## Authors

Shivyan

## License

ISC
