<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cognitive Adaptation Study</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400;600&family=Courier+Prime:wght@400;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        :root {
            --bg-primary: #0a0e14;
            --bg-secondary: #151b24;
            --accent-blue: #3d8ff5;
            --accent-red: #f53d5a;
            --text-primary: #d4d8de;
            --text-dim: #6b7785;
            --grid-color: #1a2332;
            --glow-blue: rgba(61, 143, 245, 0.3);
            --glow-red: rgba(245, 61, 90, 0.3);
        }
        
        body {
            font-family: 'JetBrains Mono', monospace;
            background: var(--bg-primary);
            color: var(--text-primary);
            overflow-x: hidden;
            line-height: 1.6;
        }
        
        /* Grid background effect */
        body::before {
            content: '';
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(var(--grid-color) 1px, transparent 1px),
                linear-gradient(90deg, var(--grid-color) 1px, transparent 1px);
            background-size: 30px 30px;
            opacity: 0.3;
            pointer-events: none;
            z-index: 0;
        }
        
        .container {
            position: relative;
            max-width: 1400px;
            margin: 0 auto;
            padding: 40px 20px;
            z-index: 1;
        }
        
        header {
            text-align: center;
            margin-bottom: 40px;
            border-bottom: 2px solid var(--grid-color);
            padding-bottom: 30px;
        }
        
        h1 {
            font-family: 'Courier Prime', monospace;
            font-size: 2.5rem;
            font-weight: 700;
            letter-spacing: -1px;
            margin-bottom: 10px;
            text-transform: uppercase;
            background: linear-gradient(135deg, var(--accent-blue), var(--accent-red));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .subtitle {
            font-size: 0.85rem;
            color: var(--text-dim);
            letter-spacing: 2px;
            text-transform: uppercase;
        }
        
        .game-area {
            background: var(--bg-secondary);
            border: 1px solid var(--grid-color);
            border-radius: 8px;
            padding: 60px 40px;
            margin-bottom: 40px;
            position: relative;
            overflow: hidden;
        }
        
        .game-area::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 2px;
            background: linear-gradient(90deg, transparent, var(--accent-blue), transparent);
            animation: scan 3s linear infinite;
        }
        
        @keyframes scan {
            0%, 100% { opacity: 0; }
            50% { opacity: 1; }
        }
        
        .status-bar {
            display: flex;
            justify-content: space-between;
            margin-bottom: 40px;
            font-size: 0.8rem;
            color: var(--text-dim);
        }
        
        .status-item {
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .status-value {
            color: var(--text-primary);
            font-weight: 600;
            font-size: 1rem;
        }
        
        .stimulus-container {
            position: relative;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 30px;
        }
        
        .stimulus {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            position: absolute;
            opacity: 0;
            transition: opacity 0.1s ease, transform 0.1s ease;
            box-shadow: 0 0 40px currentColor;
        }
        
        .stimulus.active {
            opacity: 1;
            animation: pulse 0.6s ease-in-out;
        }
        
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }
        
        .stimulus.blue {
            background: var(--accent-blue);
            color: var(--glow-blue);
        }
        
        .stimulus.red {
            background: var(--accent-red);
            color: var(--glow-red);
        }
        
        .controls {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin-bottom: 30px;
        }
        
        .key-hint {
            background: var(--bg-primary);
            border: 2px solid var(--grid-color);
            padding: 20px 40px;
            border-radius: 6px;
            font-size: 1.2rem;
            font-weight: 600;
            letter-spacing: 1px;
            transition: all 0.15s ease;
        }
        
        .key-hint.left {
            border-color: var(--accent-blue);
            color: var(--accent-blue);
        }
        
        .key-hint.right {
            border-color: var(--accent-red);
            color: var(--accent-red);
        }
        
        .key-hint.active {
            transform: scale(0.95);
            box-shadow: inset 0 0 20px currentColor;
        }
        
        .rule-display {
            text-align: center;
            padding: 20px;
            background: var(--bg-primary);
            border: 1px solid var(--grid-color);
            border-radius: 6px;
            margin-bottom: 30px;
            font-size: 0.9rem;
        }
        
        .rule-change-alert {
            color: var(--accent-red);
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 1px;
            animation: flash 0.5s ease-in-out 3;
        }
        
        @keyframes flash {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.3; }
        }
        
        .btn {
            background: var(--bg-primary);
            color: var(--text-primary);
            border: 2px solid var(--accent-blue);
            padding: 14px 32px;
            font-family: 'JetBrains Mono', monospace;
            font-size: 0.9rem;
            font-weight: 600;
            border-radius: 4px;
            cursor: pointer;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.2s ease;
            display: inline-block;
        }
        
        .btn:hover {
            background: var(--accent-blue);
            color: var(--bg-primary);
            box-shadow: 0 0 20px var(--glow-blue);
        }
        
        .btn:disabled {
            opacity: 0.4;
            cursor: not-allowed;
            border-color: var(--text-dim);
        }
        
        .btn:disabled:hover {
            background: var(--bg-primary);
            color: var(--text-primary);
            box-shadow: none;
        }
        
        .charts-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .chart-wrapper {
            background: var(--bg-secondary);
            border: 1px solid var(--grid-color);
            border-radius: 8px;
            padding: 25px;
        }
        
        .chart-title {
            font-size: 0.85rem;
            color: var(--text-dim);
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .chart-title::before {
            content: '';
            width: 3px;
            height: 14px;
            background: var(--accent-blue);
        }
        
        canvas {
            max-width: 100%;
            height: auto;
        }
        
        .model-params {
            background: var(--bg-secondary);
            border: 1px solid var(--grid-color);
            border-radius: 8px;
            padding: 25px;
            margin-top: 40px;
        }
        
        .param-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .param-control {
            display: flex;
            flex-direction: column;
            gap: 8px;
        }
        
        .param-label {
            font-size: 0.75rem;
            color: var(--text-dim);
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        
        .param-input {
            background: var(--bg-primary);
            border: 1px solid var(--grid-color);
            color: var(--text-primary);
            padding: 8px 12px;
            font-family: 'JetBrains Mono', monospace;
            font-size: 0.9rem;
            border-radius: 4px;
            width: 100%;
        }
        
        .param-input:focus {
            outline: none;
            border-color: var(--accent-blue);
            box-shadow: 0 0 10px var(--glow-blue);
        }
        
        .feedback {
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 3rem;
            font-weight: 700;
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.3s ease;
            z-index: 100;
            text-shadow: 0 0 20px currentColor;
        }
        
        .feedback.show {
            opacity: 1;
            animation: feedbackFade 0.6s ease forwards;
        }
        
        @keyframes feedbackFade {
            0% { opacity: 0; transform: translate(-50%, -50%) scale(0.8); }
            30% { opacity: 1; transform: translate(-50%, -50%) scale(1); }
            100% { opacity: 0; transform: translate(-50%, -50%) scale(1.2); }
        }
        
        .feedback.correct {
            color: #4ade80;
        }
        
        .feedback.incorrect {
            color: var(--accent-red);
        }
        
        .instructions {
            background: var(--bg-secondary);
            border: 1px solid var(--grid-color);
            border-radius: 8px;
            padding: 25px;
            margin-bottom: 30px;
            font-size: 0.9rem;
            line-height: 1.8;
        }
        
        .instructions p {
            margin-bottom: 12px;
        }
        
        .instructions strong {
            color: var(--accent-blue);
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Cognitive Adaptation Study</h1>
            <div class="subtitle">Drift-Diffusion Decision Model</div>
        </header>
        
        <div class="instructions" id="instructions">
            <p><strong>TASK:</strong> Press <strong>LEFT ARROW</strong> or <strong>RIGHT ARROW</strong> as quickly and accurately as possible when a colored circle appears.</p>
            <p><strong>INITIAL RULE:</strong> <span id="initialRule"></span></p>
            <p><strong>ADAPTATION:</strong> The rule will occasionally reverse without warning. Watch for pattern changes and adapt quickly.</p>
            <p>The system models your decisions using drift-diffusion theory, predicting your choices based on noisy evidence accumulation.</p>
        </div>
        
        <div class="game-area">
            <div class="status-bar">
                <div class="status-item">
                    <span>TRIAL:</span>
                    <span class="status-value" id="trialNum">0</span>
                </div>
                <div class="status-item">
                    <span>ACCURACY:</span>
                    <span class="status-value" id="accuracy">--</span>
                </div>
                <div class="status-item">
                    <span>AVG RT:</span>
                    <span class="status-value" id="avgRT">--</span>
                </div>
                <div class="status-item">
                    <span>RULE CHANGES:</span>
                    <span class="status-value" id="ruleChanges">0</span>
                </div>
            </div>
            
            <div class="rule-display">
                <div id="currentRule"></div>
            </div>
            
            <div class="stimulus-container">
                <div class="stimulus blue" id="stimulus"></div>
            </div>
            
            <div class="controls">
                <div class="key-hint left" id="leftKey">← LEFT</div>
                <div class="key-hint right" id="rightKey">RIGHT →</div>
            </div>
            
            <div style="text-align: center;">
                <button class="btn" id="startBtn">Initialize Experiment</button>
            </div>
        </div>
        
        <div class="charts-container">
            <div class="chart-wrapper">
                <div class="chart-title">Reaction Time Over Trials</div>
                <canvas id="rtChart" width="400" height="250"></canvas>
            </div>
            <div class="chart-wrapper">
                <div class="chart-title">Error Rate (Rolling Window)</div>
                <canvas id="errorChart" width="400" height="250"></canvas>
            </div>
            <div class="chart-wrapper">
                <div class="chart-title">Model vs Human Divergence</div>
                <canvas id="divergenceChart" width="400" height="250"></canvas>
            </div>
        </div>
        
        <div class="model-params">
            <div class="chart-title">Drift-Diffusion Model Parameters</div>
            <div class="param-grid">
                <div class="param-control">
                    <label class="param-label">Drift Rate (v)</label>
                    <input type="number" class="param-input" id="driftRate" value="0.3" step="0.05" min="0.1" max="1">
                </div>
                <div class="param-control">
                    <label class="param-label">Boundary (a)</label>
                    <input type="number" class="param-input" id="boundary" value="1.0" step="0.1" min="0.5" max="2">
                </div>
                <div class="param-control">
                    <label class="param-label">Noise (s)</label>
                    <input type="number" class="param-input" id="noise" value="0.1" step="0.01" min="0.01" max="0.5">
                </div>
                <div class="param-control">
                    <label class="param-label">Non-decision Time (ms)</label>
                    <input type="number" class="param-input" id="nonDecisionTime" value="300" step="50" min="100" max="600">
                </div>
            </div>
        </div>
    </div>
    
    <div class="feedback" id="feedback"></div>
    
    <script>
        // Cognitive modeling game state
        const gameState = {
            trials: [],
            currentTrial: 0,
            rule: Math.random() > 0.5 ? 'blue-left' : 'blue-right',
            ruleChanges: 0,
            lastRuleChange: 0,
            isActive: false,
            stimulusStartTime: 0,
            awaitingResponse: false
        };
        
        // Model parameters (adjustable)
        const modelParams = {
            driftRate: 0.3,      // Evidence accumulation rate
            boundary: 1.0,       // Decision threshold
            noise: 0.1,          // Noise in accumulation
            nonDecisionTime: 300 // Non-decision time in ms
        };
        
        // Trial data structure
        class Trial {
            constructor(number, color, position, correctResponse) {
                this.number = number;
                this.color = color;
                this.position = position;
                this.correctResponse = correctResponse;
                this.humanResponse = null;
                this.humanRT = null;
                this.humanCorrect = null;
                this.modelPrediction = null;
                this.modelRT = null;
                this.modelCorrect = null;
                this.postRuleChangeIndex = gameState.currentTrial - gameState.lastRuleChange;
            }
        }
        
        // DOM elements
        const stimulus = document.getElementById('stimulus');
        const leftKey = document.getElementById('leftKey');
        const rightKey = document.getElementById('rightKey');
        const startBtn = document.getElementById('startBtn');
        const feedback = document.getElementById('feedback');
        const currentRuleDiv = document.getElementById('currentRule');
        const initialRuleSpan = document.getElementById('initialRule');
        
        // Initialize rule display
        updateRuleDisplay();
        initialRuleSpan.textContent = getRuleText();
        
        function getRuleText() {
            return gameState.rule === 'blue-left' 
                ? 'BLUE → LEFT  |  RED → RIGHT'
                : 'BLUE → RIGHT  |  RED → LEFT';
        }
        
        function updateRuleDisplay() {
            currentRuleDiv.textContent = getRuleText();
        }
        
        // Drift-diffusion model simulation
        function simulateDDM(correctDirection) {
            const v = modelParams.driftRate * (correctDirection ? 1 : -1);
            const a = modelParams.boundary;
            const s = modelParams.noise;
            const dt = 0.001; // Time step in seconds
            
            let evidence = 0;
            let time = 0;
            const maxTime = 5; // Maximum 5 seconds
            
            // Simulate evidence accumulation
            while (Math.abs(evidence) < a && time < maxTime) {
                evidence += v * dt + s * Math.sqrt(dt) * (Math.random() * 2 - 1);
                time += dt;
            }
            
            const decision = evidence >= a ? 1 : -1;
            const reactionTime = (time * 1000) + modelParams.nonDecisionTime;
            
            return {
                decision: decision,
                rt: reactionTime,
                correct: (decision === 1) === correctDirection
            };
        }
        
        // Generate next trial
        function generateTrial() {
            const color = Math.random() > 0.5 ? 'blue' : 'red';
            const offset = (Math.random() - 0.5) * 100; // -50 to +50 pixels
            
            let correctResponse;
            if (gameState.rule === 'blue-left') {
                correctResponse = color === 'blue' ? 'left' : 'right';
            } else {
                correctResponse = color === 'blue' ? 'right' : 'left';
            }
            
            const trial = new Trial(
                gameState.currentTrial + 1,
                color,
                offset,
                correctResponse
            );
            
            // Model prediction
            const modelResult = simulateDDM(true); // Model always uses correct rule
            trial.modelPrediction = modelResult.decision === 1 ? correctResponse : (correctResponse === 'left' ? 'right' : 'left');
            trial.modelRT = modelResult.rt;
            trial.modelCorrect = modelResult.correct;
            
            return trial;
        }
        
        // Show stimulus
        function showStimulus(trial) {
            stimulus.className = `stimulus ${trial.color} active`;
            stimulus.style.left = `calc(50% + ${trial.position}px)`;
            gameState.stimulusStartTime = performance.now();
            gameState.awaitingResponse = true;
        }
        
        // Handle response
        function handleResponse(response) {
            if (!gameState.awaitingResponse || !gameState.isActive) return;
            
            gameState.awaitingResponse = false;
            const rt = performance.now() - gameState.stimulusStartTime;
            const currentTrial = gameState.trials[gameState.trials.length - 1];
            
            currentTrial.humanResponse = response;
            currentTrial.humanRT = rt;
            currentTrial.humanCorrect = response === currentTrial.correctResponse;
            
            // Visual feedback
            showFeedback(currentTrial.humanCorrect);
            stimulus.classList.remove('active');
            
            // Update stats
            updateStats();
            
            // Check for rule reversal (happens pseudo-randomly after 8-15 trials)
            const trialsSinceChange = gameState.currentTrial - gameState.lastRuleChange;
            if (trialsSinceChange >= 8 && Math.random() < 0.15) {
                reverseRule();
            }
            
            // Next trial after delay
            setTimeout(() => {
                if (gameState.isActive) {
                    startTrial();
                }
            }, 1000);
        }
        
        function reverseRule() {
            gameState.rule = gameState.rule === 'blue-left' ? 'blue-right' : 'blue-left';
            gameState.ruleChanges++;
            gameState.lastRuleChange = gameState.currentTrial;
            
            updateRuleDisplay();
            currentRuleDiv.classList.add('rule-change-alert');
            setTimeout(() => currentRuleDiv.classList.remove('rule-change-alert'), 1500);
            
            document.getElementById('ruleChanges').textContent = gameState.ruleChanges;
            updateCharts();
        }
        
        function showFeedback(correct) {
            feedback.textContent = correct ? '✓' : '✗';
            feedback.className = `feedback ${correct ? 'correct' : 'incorrect'} show`;
            setTimeout(() => feedback.classList.remove('show'), 600);
        }
        
        // Start trial
        function startTrial() {
            gameState.currentTrial++;
            const trial = generateTrial();
            gameState.trials.push(trial);
            
            document.getElementById('trialNum').textContent = gameState.currentTrial;
            
            // Inter-trial interval
            setTimeout(() => {
                showStimulus(trial);
            }, 500 + Math.random() * 500);
        }
        
        // Update statistics
        function updateStats() {
            const recentTrials = gameState.trials.filter(t => t.humanCorrect !== null);
            if (recentTrials.length === 0) return;
            
            const accuracy = recentTrials.filter(t => t.humanCorrect).length / recentTrials.length;
            const avgRT = recentTrials.reduce((sum, t) => sum + t.humanRT, 0) / recentTrials.length;
            
            document.getElementById('accuracy').textContent = `${(accuracy * 100).toFixed(1)}%`;
            document.getElementById('avgRT').textContent = `${avgRT.toFixed(0)}ms`;
            
            updateCharts();
        }
        
        // Chart drawing
        function drawChart(canvasId, data, options) {
            const canvas = document.getElementById(canvasId);
            const ctx = canvas.getContext('2d');
            const width = canvas.width;
            const height = canvas.height;
            const padding = 40;
            
            ctx.clearRect(0, 0, width, height);
            
            if (data.length === 0) return;
            
            // Find data range
            const xValues = data.map((d, i) => i);
            const yValues = data.map(d => d.y);
            const xMin = 0;
            const xMax = Math.max(...xValues, 1);
            const yMin = Math.min(...yValues, options.yMin || 0);
            const yMax = Math.max(...yValues, options.yMax || 1);
            const yRange = yMax - yMin || 1;
            
            // Draw grid
            ctx.strokeStyle = '#1a2332';
            ctx.lineWidth = 1;
            for (let i = 0; i <= 5; i++) {
                const y = padding + (height - 2 * padding) * (i / 5);
                ctx.beginPath();
                ctx.moveTo(padding, y);
                ctx.lineTo(width - padding, y);
                ctx.stroke();
            }
            
            // Draw axes
            ctx.strokeStyle = '#6b7785';
            ctx.lineWidth = 2;
            ctx.beginPath();
            ctx.moveTo(padding, padding);
            ctx.lineTo(padding, height - padding);
            ctx.lineTo(width - padding, height - padding);
            ctx.stroke();
            
            // Draw rule change markers
            ctx.strokeStyle = '#f53d5a';
            ctx.lineWidth = 1;
            ctx.setLineDash([5, 5]);
            gameState.trials.forEach((trial, i) => {
                if (trial.postRuleChangeIndex === 0 && i > 0) {
                    const x = padding + (width - 2 * padding) * (i / xMax);
                    ctx.beginPath();
                    ctx.moveTo(x, padding);
                    ctx.lineTo(x, height - padding);
                    ctx.stroke();
                }
            });
            ctx.setLineDash([]);
            
            // Draw data
            if (options.drawModel && data[0].model !== undefined) {
                // Model prediction
                ctx.strokeStyle = '#3d8ff5';
                ctx.lineWidth = 2;
                ctx.globalAlpha = 0.5;
                ctx.beginPath();
                data.forEach((d, i) => {
                    const x = padding + (width - 2 * padding) * (i / xMax);
                    const y = height - padding - (height - 2 * padding) * ((d.model - yMin) / yRange);
                    if (i === 0) ctx.moveTo(x, y);
                    else ctx.lineTo(x, y);
                });
                ctx.stroke();
                ctx.globalAlpha = 1;
            }
            
            // Human data
            ctx.strokeStyle = options.color || '#d4d8de';
            ctx.lineWidth = 2;
            ctx.beginPath();
            data.forEach((d, i) => {
                if (d.y === null) return;
                const x = padding + (width - 2 * padding) * (i / xMax);
                const y = height - padding - (height - 2 * padding) * ((d.y - yMin) / yRange);
                if (i === 0) ctx.moveTo(x, y);
                else ctx.lineTo(x, y);
            });
            ctx.stroke();
            
            // Draw points
            data.forEach((d, i) => {
                if (d.y === null) return;
                const x = padding + (width - 2 * padding) * (i / xMax);
                const y = height - padding - (height - 2 * padding) * ((d.y - yMin) / yRange);
                ctx.fillStyle = d.correct ? '#4ade80' : '#f53d5a';
                ctx.beginPath();
                ctx.arc(x, y, 3, 0, Math.PI * 2);
                ctx.fill();
            });
            
            // Labels
            ctx.fillStyle = '#6b7785';
            ctx.font = '10px JetBrains Mono';
            ctx.fillText(yMax.toFixed(options.precision || 0), 5, padding);
            ctx.fillText(yMin.toFixed(options.precision || 0), 5, height - padding);
        }
        
        function updateCharts() {
            const completedTrials = gameState.trials.filter(t => t.humanRT !== null);
            
            // RT Chart
            const rtData = completedTrials.map(t => ({
                y: t.humanRT,
                model: t.modelRT,
                correct: t.humanCorrect
            }));
            drawChart('rtChart', rtData, {
                color: '#3d8ff5',
                yMin: 200,
                yMax: Math.max(...rtData.map(d => Math.max(d.y, d.model)), 1000),
                drawModel: true,
                precision: 0
            });
            
            // Error rate (rolling window of 10)
            const windowSize = 10;
            const errorData = completedTrials.map((t, i) => {
                const window = completedTrials.slice(Math.max(0, i - windowSize + 1), i + 1);
                const errorRate = 1 - (window.filter(w => w.humanCorrect).length / window.length);
                const modelErrorRate = 1 - (window.filter(w => w.modelCorrect).length / window.length);
                return {
                    y: errorRate,
                    model: modelErrorRate,
                    correct: t.humanCorrect
                };
            });
            drawChart('errorChart', errorData, {
                color: '#f53d5a',
                yMin: 0,
                yMax: 1,
                drawModel: true,
                precision: 2
            });
            
            // Divergence (absolute difference between human and model)
            const divergenceData = completedTrials.map(t => ({
                y: Math.abs(t.humanRT - t.modelRT) / 1000, // in seconds
                correct: t.humanCorrect
            }));
            drawChart('divergenceChart', divergenceData, {
                color: '#fbbf24',
                yMin: 0,
                yMax: Math.max(...divergenceData.map(d => d.y), 1),
                precision: 2
            });
        }
        
        // Event handlers
        startBtn.addEventListener('click', () => {
            if (!gameState.isActive) {
                gameState.isActive = true;
                startBtn.textContent = 'Stop Experiment';
                startBtn.style.borderColor = 'var(--accent-red)';
                document.getElementById('instructions').style.display = 'none';
                startTrial();
            } else {
                gameState.isActive = false;
                startBtn.textContent = 'Resume Experiment';
                startBtn.style.borderColor = 'var(--accent-blue)';
                stimulus.classList.remove('active');
            }
        });
        
        document.addEventListener('keydown', (e) => {
            if (e.key === 'ArrowLeft') {
                leftKey.classList.add('active');
                handleResponse('left');
            } else if (e.key === 'ArrowRight') {
                rightKey.classList.add('active');
                handleResponse('right');
            }
        });
        
        document.addEventListener('keyup', (e) => {
            if (e.key === 'ArrowLeft') {
                leftKey.classList.remove('active');
            } else if (e.key === 'ArrowRight') {
                rightKey.classList.remove('active');
            }
        });
        
        // Model parameter updates
        document.getElementById('driftRate').addEventListener('input', (e) => {
            modelParams.driftRate = parseFloat(e.target.value);
        });
        document.getElementById('boundary').addEventListener('input', (e) => {
            modelParams.boundary = parseFloat(e.target.value);
        });
        document.getElementById('noise').addEventListener('input', (e) => {
            modelParams.noise = parseFloat(e.target.value);
        });
        document.getElementById('nonDecisionTime').addEventListener('input', (e) => {
            modelParams.nonDecisionTime = parseFloat(e.target.value);
        });
    </script>
</body>
</html>
