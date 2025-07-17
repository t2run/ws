# Websocket tool

A professional, modern WebSocket tool with a sleek sidebar interface for developers and QA engineers. Test WebSocket connections, send/receive messages, and monitor real-time statistics with an intuitive user experience.

## ✨ Features

### 🎨 Modern Sidebar Design
- **Professional Navigation**: Dark sidebar with smooth transitions and tab-based navigation
- **Active State Indicators**: Color-coded tabs with visual feedback
- **Mobile Responsive**: Collapsible sidebar that adapts to all screen sizes
- **Smooth Animations**: Polished hover effects and transitions throughout

### 🔧 Core Functionality
- **WebSocket Connection Management**: Connect, disconnect, and monitor connection status
- **Real-time Messaging**: Send and receive messages with timestamp tracking
- **Connection History**: Track all connection attempts with status and timestamps
- **Custom Headers**: Configure WebSocket headers for authentication and protocols
- **Statistics Dashboard**: Monitor connection metrics and data transfer

### 📊 Advanced Features
- **Real-time Statistics**: Track messages sent/received, data transferred, and connection time
- **Configuration Management**: Save and load connection configurations with timestamps
- **Enhanced Error Handling**: Comprehensive error reporting and user feedback
- **Keyboard Shortcuts**: Quick actions (Enter to send messages)
- **Auto-scrolling Message Log**: Terminal-like interface with custom scrollbars

### 🎯 Professional UI/UX
- **Gradient Design Elements**: Modern gradient buttons and headers
- **Dark Theme Message Log**: Terminal-style message display
- **Pulse Animations**: Visual connection status indicators
- **Professional Typography**: Clean, readable fonts and proper spacing
- **Touch-friendly Controls**: Optimized for mobile and tablet use

## 🚀 Quick Start

### Prerequisites
- Modern web browser with WebSocket support
- WebSocket server to test against (optional for demo)

### Installation

1. **Clone or Download**: Save the HTML file to your local machine
2. **Open in Browser**: Double-click the file or serve it via a local server
3. **Start Testing**: Enter a WebSocket URL and begin testing


## 📖 Usage Guide

### Basic Connection

1. **Navigate to Connection Tab**: Click the "Connection" tab in the sidebar
2. **Enter WebSocket URL**: Input your WebSocket server URL (e.g., `ws://localhost:8080`)
3. **Configure Headers** (Optional): Switch to "Headers" tab to add custom headers
4. **Connect**: Click the "Connect" button
5. **Monitor Status**: Watch the connection status indicator at the top

### Sending Messages

1. **Go to Messages Tab**: Click "Messages" in the sidebar
2. **Type Your Message**: Enter text in the message input field
3. **Send**: Click "Send Message" or press Enter
4. **View Response**: Monitor incoming messages in the message log

### Managing Configurations

1. **Access Configurations**: Click the "Configurations" tab
2. **Save Current Setup**: Click "Save Configuration" to store current settings
3. **Load Saved Config**: Select from saved configurations and click "Load"
4. **View History**: Check timestamps and connection details

### Monitoring Statistics

1. **View Statistics Tab**: Click "Statistics" to see real-time metrics
2. **Monitor Metrics**: Track messages sent/received, data transferred, and connection time
3. **Connection History**: Review past connections with status and timestamps

## 🔧 Configuration Options

### Connection Settings
- **WebSocket URL**: Target server endpoint
- **Protocol**: WebSocket sub-protocol (optional)
- **Connection Timeout**: Automatic timeout settings

## 🎨 Interface Overview

### Sidebar Navigation
- **Connection**: Main connection controls and URL input
- **Messages**: Message sending interface and history
- **Configurations**: Save/load connection presets
- **Headers**: Custom WebSocket headers configuration
- **Statistics**: Real-time metrics and connection history

### Status Indicators
- 🟢 **Connected**: Active WebSocket connection
- 🔴 **Disconnected**: No active connection
- 🟡 **Connecting**: Connection in progress
- ⚠️ **Error**: Connection failed or error occurred

### Message Log Features
- **Timestamp Display**: Each message shows send/receive time
- **Message Direction**: Clear indicators for sent vs. received
- **Auto-scroll**: Automatically scrolls to latest messages
- **Copy Support**: Click messages to copy content

## 🔍 Troubleshooting

### Common Issues

**Connection Refused**
- Verify WebSocket server is running
- Check URL format (ws:// or wss://)
- Ensure firewall allows WebSocket connections

**CORS Errors**
- Add appropriate Origin headers
- Configure server to allow cross-origin requests
- Use proper authentication headers

**Message Not Sending**
- Ensure connection is established (green status)
- Check message format requirements
- Verify server is accepting messages

**Performance Issues**
- Clear message history periodically
- Limit message frequency for high-volume testing
- Check browser console for errors

## 🛠️ Development

### File Structure
```
websocket-tester/
├── index.html          # Main application file
├── README.md           # This documentation
```

### Key Technologies
- **HTML5**: Structure and WebSocket API
- **CSS3**: Styling, animations, and responsive design
- **Vanilla JavaScript**: Core functionality and WebSocket handling
- **Flexbox/Grid**: Layout system
- **CSS Variables**: Theme customization

## 🤝 Contributing

1. **Fork the Project**: Create your own copy
2. **Create Feature Branch**: `git checkout -b feature/new-feature`
3. **Commit Changes**: `git commit -m 'Add new feature'`
4. **Push to Branch**: `git push origin feature/new-feature`
5. **Open Pull Request**: Submit your changes

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- WebSocket API documentation from MDN
- Modern CSS techniques from various web development resources
- Color schemes from modern design systems
