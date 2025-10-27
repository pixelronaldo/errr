<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UltraDDoS Pro - Advanced Network Stress Tool</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0c0c0c, #1a1a2e);
            color: #e0e0e0;
            min-height: 100vh;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            text-align: center;
            padding: 30px 0;
            border-bottom: 1px solid #333;
            margin-bottom: 30px;
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #ff4d4d, #ff9966);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            text-shadow: 0 0 10px rgba(255, 77, 77, 0.3);
        }
        
        .subtitle {
            font-size: 1.2rem;
            color: #aaa;
            margin-bottom: 20px;
        }
        
        .warning {
            background: rgba(255, 77, 77, 0.1);
            border: 1px solid #ff4d4d;
            border-radius: 5px;
            padding: 15px;
            margin: 20px 0;
            text-align: center;
            color: #ff9999;
        }
        
        .panel {
            background: rgba(30, 30, 46, 0.7);
            border-radius: 10px;
            padding: 25px;
            margin-bottom: 25px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
            border: 1px solid #333;
        }
        
        h2 {
            color: #ff9966;
            margin-bottom: 20px;
            font-size: 1.6rem;
        }
        
        .input-group {
            margin-bottom: 20px;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            color: #ccc;
        }
        
        input, select {
            width: 100%;
            padding: 12px;
            background: rgba(20, 20, 30, 0.8);
            border: 1px solid #444;
            border-radius: 5px;
            color: #e0e0e0;
            font-size: 1rem;
        }
        
        .btn {
            background: linear-gradient(90deg, #ff4d4d, #ff9966);
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            font-weight: bold;
            transition: all 0.3s;
            margin-right: 10px;
            margin-bottom: 10px;
        }
        
        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(255, 77, 77, 0.4);
        }
        
        .btn:active {
            transform: translateY(0);
        }
        
        .btn-stop {
            background: linear-gradient(90deg, #4d79ff, #66a3ff);
        }
        
        .btn-clear {
            background: linear-gradient(90deg, #4dff4d, #66ff99);
        }
        
        .progress-container {
            margin: 30px 0;
        }
        
        .progress-bar {
            height: 25px;
            background: rgba(20, 20, 30, 0.8);
            border-radius: 5px;
            overflow: hidden;
            margin-bottom: 10px;
            border: 1px solid #444;
        }
        
        .progress {
            height: 100%;
            background: linear-gradient(90deg, #ff4d4d, #ff9966);
            width: 0%;
            transition: width 0.5s;
        }
        
        .progress-info {
            display: flex;
            justify-content: space-between;
            color: #aaa;
            font-size: 0.9rem;
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }
        
        .stat-box {
            background: rgba(20, 20, 30, 0.8);
            border-radius: 5px;
            padding: 15px;
            text-align: center;
            border: 1px solid #444;
        }
        
        .stat-value {
            font-size: 1.8rem;
            font-weight: bold;
            color: #ff9966;
            margin: 10px 0;
        }
        
        .log-container {
            background: rgba(10, 10, 15, 0.8);
            border-radius: 5px;
            padding: 15px;
            height: 200px;
            overflow-y: auto;
            font-family: monospace;
            font-size: 0.9rem;
            border: 1px solid #444;
        }
        
        .log-entry {
            margin-bottom: 5px;
            padding: 5px;
            border-bottom: 1px solid #222;
        }
        
        .log-time {
            color: #66a3ff;
        }
        
        .log-info {
            color: #66ff99;
        }
        
        .log-warning {
            color: #ff9966;
        }
        
        .log-error {
            color: #ff4d4d;
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #666;
            font-size: 0.9rem;
            border-top: 1px solid #333;
        }
        
        .disclaimer {
            font-size: 0.8rem;
            color: #555;
            margin-top: 10px;
        }
        
        .flashing {
            animation: flash 1s infinite;
        }
        
        @keyframes flash {
            0% { opacity: 1; }
            50% { opacity: 0.5; }
            100% { opacity: 1; }
        }
        
        .attack-status {
            text-align: center;
            padding: 15px;
            border-radius: 5px;
            margin: 20px 0;
            font-weight: bold;
            display: none;
        }
        
        .status-active {
            background: rgba(255, 77, 77, 0.2);
            color: #ff4d4d;
            border: 1px solid #ff4d4d;
        }
        
        .status-stopped {
            background: rgba(77, 121, 255, 0.2);
            color: #4d79ff;
            border: 1px solid #4d79ff;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>UltraDDoS Pro</h1>
            <div class="subtitle">Advanced Network Stress Testing Tool - For Educational Purposes Only</div>
            <div class="warning">
                <strong>WARNING:</strong> This tool is for educational and authorized testing purposes only. 
                Unauthorized use against networks you do not own or have explicit permission to test is illegal.
            </div>
        </header>
        
        <div class="panel">
            <h2>Attack Configuration</h2>
            
            <div class="input-group">
                <label for="target">Target IP / Domain</label>
                <input type="text" id="target" placeholder="example.com or 192.168.1.1">
            </div>
            
            <div class="input-group">
                <label for="port">Target Port</label>
                <input type="text" id="port" placeholder="80 (HTTP) or 443 (HTTPS)" value="80">
            </div>
            
            <div class="input-group">
                <label for="method">Attack Method</label>
                <select id="method">
                    <option value="udp">UDP Flood</option>
                    <option value="tcp">TCP SYN Flood</option>
                    <option value="http">HTTP GET Flood</option>
                    <option value="icmp">ICMP Flood</option>
                    <option value="slowloris">Slowloris</option>
                </select>
            </div>
            
            <div class="input-group">
                <label for="threads">Threads</label>
                <input type="range" id="threads" min="1" max="1000" value="100">
                <div class="progress-info">
                    <span>Low</span>
                    <span id="threads-value">100 threads</span>
                    <span>High</span>
                </div>
            </div>
            
            <div class="input-group">
                <label for="duration">Duration (seconds)</label>
                <input type="number" id="duration" min="10" max="3600" value="60">
            </div>
            
            <button class="btn" id="start-btn">LAUNCH ATTACK</button>
            <button class="btn btn-stop" id="stop-btn">STOP ATTACK</button>
            <button class="btn btn-clear" id="clear-btn">CLEAR LOGS</button>
        </div>
        
        <div class="attack-status status-stopped" id="status">
            Attack Status: STOPPED
        </div>
        
        <div class="panel">
            <h2>Attack Progress</h2>
            
            <div class="progress-container">
                <div class="progress-bar">
                    <div class="progress" id="attack-progress"></div>
                </div>
                <div class="progress-info">
                    <span>Initializing</span>
                    <span id="progress-text">0%</span>
                    <span>Complete</span>
                </div>
            </div>
            
            <div class="stats">
                <div class="stat-box">
                    <div>Packets Sent</div>
                    <div class="stat-value" id="packets-sent">0</div>
                    <div>per second</div>
                </div>
                <div class="stat-box">
                    <div>Data Transferred</div>
                    <div class="stat-value" id="data-sent">0 MB</div>
                    <div>total</div>
                </div>
                <div class="stat-box">
                    <div>Attack Duration</div>
                    <div class="stat-value" id="attack-duration">0s</div>
                    <div>elapsed</div>
                </div>
                <div class="stat-box">
                    <div>Active Threads</div>
                    <div class="stat-value" id="active-threads">0</div>
                    <div>of 100</div>
                </div>
            </div>
        </div>
        
        <div class="panel">
            <h2>Attack Log</h2>
            <div class="log-container" id="log-container">
                <div class="log-entry">
                    <span class="log-time">[12:00:00]</span> 
                    <span class="log-info">System initialized. Ready for attack configuration.</span>
                </div>
                <div class="log-entry">
                    <span class="log-time">[12:00:00]</span> 
                    <span class="log-warning">WARNING: Use this tool responsibly and only on networks you own.</span>
                </div>
            </div>
        </div>
        
        <footer>
            <p>UltraDDoS Pro v2.1.4 - Network Stress Testing Tool</p>
            <p class="disclaimer">
                This is a simulation tool for educational purposes only. No actual network attacks are performed by this application.
                The developer is not responsible for any misuse of this tool.
            </p>
        </footer>
    </div>

    <script>
        // DOM Elements
        const startBtn = document.getElementById('start-btn');
        const stopBtn = document.getElementById('stop-btn');
        const clearBtn = document.getElementById('clear-btn');
        const targetInput = document.getElementById('target');
        const portInput = document.getElementById('port');
        const methodSelect = document.getElementById('method');
        const threadsSlider = document.getElementById('threads');
        const threadsValue = document.getElementById('threads-value');
        const durationInput = document.getElementById('duration');
        const statusDiv = document.getElementById('status');
        const progressBar = document.getElementById('attack-progress');
        const progressText = document.getElementById('progress-text');
        const packetsSent = document.getElementById('packets-sent');
        const dataSent = document.getElementById('data-sent');
        const attackDuration = document.getElementById('attack-duration');
        const activeThreads = document.getElementById('active-threads');
        const logContainer = document.getElementById('log-container');
        
        // State variables
        let attackActive = false;
        let attackInterval;
        let elapsedTime = 0;
        let totalPackets = 0;
        let totalData = 0;
        
        // Update threads value display
        threadsSlider.addEventListener('input', function() {
            threadsValue.textContent = `${this.value} threads`;
        });
        
        // Add log entry
        function addLogEntry(message, type = 'info') {
            const now = new Date();
            const timeString = `[${now.getHours().toString().padStart(2, '0')}:${now.getMinutes().toString().padStart(2, '0')}:${now.getSeconds().toString().padStart(2, '0')}]`;
            
            const logEntry = document.createElement('div');
            logEntry.className = 'log-entry';
            logEntry.innerHTML = `<span class="log-time">${timeString}</span> <span class="log-${type}">${message}</span>`;
            
            logContainer.appendChild(logEntry);
            logContainer.scrollTop = logContainer.scrollHeight;
        }
        
        // Start attack simulation
        startBtn.addEventListener('click', function() {
            if (attackActive) return;
            
            const target = targetInput.value.trim();
            const port = portInput.value.trim();
            const method = methodSelect.value;
            const threads = parseInt(threadsSlider.value);
            const duration = parseInt(durationInput.value);
            
            if (!target) {
                addLogEntry('ERROR: Please specify a target IP or domain.', 'error');
                return;
            }
            
            if (!port || isNaN(port)) {
                addLogEntry('ERROR: Please specify a valid port number.', 'error');
                return;
            }
            
            attackActive = true;
            elapsedTime = 0;
            totalPackets = 0;
            totalData = 0;
            
            // Update UI
            statusDiv.textContent = `Attack Status: ATTACKING ${target}:${port} with ${method.toUpperCase()} (${threads} threads)`;
            statusDiv.className = 'attack-status status-active flashing';
            statusDiv.style.display = 'block';
            
            progressBar.style.width = '0%';
            progressText.textContent = '0%';
            packetsSent.textContent = '0';
            dataSent.textContent = '0 MB';
            attackDuration.textContent = '0s';
            activeThreads.textContent = '0';
            
            addLogEntry(`Starting ${method.toUpperCase()} attack on ${target}:${port}`, 'info');
            addLogEntry(`Launching ${threads} attack threads...`, 'info');
            
            // Simulate thread initialization
            let threadsStarted = 0;
            const threadInterval = setInterval(() => {
                threadsStarted += Math.floor(Math.random() * 10) + 5;
                if (threadsStarted > threads) threadsStarted = threads;
                
                activeThreads.textContent = threadsStarted.toString();
                
                if (threadsStarted >= threads) {
                    clearInterval(threadInterval);
                    addLogEntry(`All ${threads} threads successfully launched. Attack in progress...`, 'info');
                }
            }, 200);
            
            // Start attack simulation
            attackInterval = setInterval(() => {
                elapsedTime++;
                
                // Update progress
                const progressPercent = Math.min(100, Math.floor((elapsedTime / duration) * 100));
                progressBar.style.width = `${progressPercent}%`;
                progressText.textContent = `${progressPercent}%`;
                
                // Update stats
                const packetsThisSecond = Math.floor(Math.random() * 10000) + 5000;
                totalPackets += packetsThisSecond;
                packetsSent.textContent = totalPackets.toLocaleString();
                
                const dataThisSecond = packetsThisSecond * (Math.random() * 100 + 50);
                totalData += dataThisSecond;
                dataSent.textContent = (totalData / (1024 * 1024)).toFixed(2) + ' MB';
                
                attackDuration.textContent = `${elapsedTime}s`;
                
                // Random log entries during attack
                if (Math.random() < 0.3) {
                    const logMessages = [
                        `Sent ${packetsThisSecond.toLocaleString()} packets to ${target}`,
                        `Thread ${Math.floor(Math.random() * threads) + 1} responding normally`,
                        `Target response time: ${(Math.random() * 500 + 100).toFixed(0)}ms`,
                        `Network buffer utilization: ${Math.floor(Math.random() * 80) + 20}%`
                    ];
                    addLogEntry(logMessages[Math.floor(Math.random() * logMessages.length)]);
                }
                
                // Check if attack should complete
                if (elapsedTime >= duration) {
                    stopAttack();
                    addLogEntry(`Attack completed after ${duration} seconds.`, 'info');
                    addLogEntry(`Total packets sent: ${totalPackets.toLocaleString()}`, 'info');
                    addLogEntry(`Total data transferred: ${(totalData / (1024 * 1024)).toFixed(2)} MB`, 'info');
                }
            }, 1000);
        });
        
        // Stop attack
        stopBtn.addEventListener('click', stopAttack);
        
        function stopAttack() {
            if (!attackActive) return;
            
            clearInterval(attackInterval);
            attackActive = false;
            
            statusDiv.textContent = 'Attack Status: STOPPED';
            statusDiv.className = 'attack-status status-stopped';
            statusDiv.style.display = 'block';
            
            activeThreads.textContent = '0';
            addLogEntry('Attack stopped by user.', 'warning');
        }
        
        // Clear logs
        clearBtn.addEventListener('click', function() {
            logContainer.innerHTML = '';
            addLogEntry('Log cleared.', 'info');
        });
        
        // Add initial log entry
        setTimeout(() => {
            addLogEntry('System ready. Configure target and parameters to begin.', 'info');
        }, 1000);
    </script>
</body>
</html>
