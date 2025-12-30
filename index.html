<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Superintelligence Outcome Simulator</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: #e2e8f0;
            min-height: 100vh;
            padding: 20px;
        }
        
        .container {
            max-width: 1400px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            margin-bottom: 30px;
            padding: 20px;
            background: rgba(30, 41, 59, 0.7);
            border-radius: 15px;
            border: 1px solid #475569;
        }
        
        h1 {
            font-size: 2.8rem;
            background: linear-gradient(90deg, #60a5fa, #38bdf8);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-size: 1.2rem;
            color: #94a3b8;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
        }
        
        .dashboard {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 25px;
            margin-bottom: 30px;
        }
        
        @media (max-width: 1100px) {
            .dashboard {
                grid-template-columns: 1fr;
            }
        }
        
        .card {
            background: rgba(30, 41, 59, 0.8);
            border-radius: 15px;
            padding: 25px;
            border: 1px solid #475569;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
        }
        
        .card-title {
            font-size: 1.5rem;
            color: #38bdf8;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .card-title i {
            font-size: 1.3rem;
        }
        
        .probability-bars {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        
        .probability-item {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 10px;
        }
        
        .probability-label {
            display: flex;
            align-items: center;
            gap: 10px;
            width: 40%;
        }
        
        .probability-bar-container {
            width: 55%;
            height: 30px;
            background: #1e293b;
            border-radius: 5px;
            overflow: hidden;
            position: relative;
        }
        
        .probability-bar {
            height: 100%;
            border-radius: 5px;
            display: flex;
            align-items: center;
            justify-content: flex-end;
            padding-right: 10px;
            font-weight: bold;
            transition: width 1.5s ease;
        }
        
        .bar-1 { background: linear-gradient(90deg, #10b981, #34d399); }
        .bar-2 { background: linear-gradient(90deg, #3b82f6, #60a5fa); }
        .bar-3 { background: linear-gradient(90deg, #f59e0b, #fbbf24); }
        .bar-4 { background: linear-gradient(90deg, #ef4444, #f87171); }
        .bar-5 { background: linear-gradient(90deg, #8b5cf6, #a78bfa); }
        
        .probability-value {
            font-weight: bold;
            font-size: 1.1rem;
            min-width: 50px;
            text-align: right;
        }
        
        .controls {
            display: flex;
            flex-direction: column;
            gap: 20px;
        }
        
        .slider-container {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        
        .slider-label {
            display: flex;
            justify-content: space-between;
        }
        
        .slider {
            -webkit-appearance: none;
            width: 100%;
            height: 10px;
            border-radius: 5px;
            background: #475569;
            outline: none;
        }
        
        .slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            width: 22px;
            height: 22px;
            border-radius: 50%;
            background: #38bdf8;
            cursor: pointer;
            border: 2px solid #0f172a;
        }
        
        .scenario-details {
            height: 350px;
            overflow-y: auto;
            padding-right: 10px;
        }
        
        .scenario-details::-webkit-scrollbar {
            width: 8px;
        }
        
        .scenario-details::-webkit-scrollbar-track {
            background: #1e293b;
            border-radius: 4px;
        }
        
        .scenario-details::-webkit-scrollbar-thumb {
            background: #475569;
            border-radius: 4px;
        }
        
        .scenario-card {
            background: rgba(15, 23, 42, 0.7);
            border-radius: 10px;
            padding: 15px;
            margin-bottom: 15px;
            border-left: 4px solid;
            cursor: pointer;
            transition: background 0.3s;
        }
        
        .scenario-card:hover {
            background: rgba(30, 41, 59, 0.9);
        }
        
        .scenario-card.active {
            background: rgba(56, 189, 248, 0.15);
            border-left-width: 6px;
        }
        
        .scenario-1 { border-color: #10b981; }
        .scenario-2 { border-color: #3b82f6; }
        .scenario-3 { border-color: #f59e0b; }
        .scenario-4 { border-color: #ef4444; }
        .scenario-5 { border-color: #8b5cf6; }
        
        .scenario-title {
            font-size: 1.2rem;
            margin-bottom: 8px;
            display: flex;
            justify-content: space-between;
        }
        
        .scenario-desc {
            color: #cbd5e1;
            font-size: 0.95rem;
            line-height: 1.5;
        }
        
        .simulation-section {
            margin-top: 30px;
        }
        
        .simulation-controls {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 25px 0;
        }
        
        .btn {
            padding: 12px 24px;
            border-radius: 8px;
            border: none;
            font-size: 1rem;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .btn-primary {
            background: linear-gradient(90deg, #3b82f6, #2563eb);
            color: white;
        }
        
        .btn-secondary {
            background: rgba(30, 41, 59, 0.9);
            color: #e2e8f0;
            border: 1px solid #475569;
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 7px 15px rgba(0, 0, 0, 0.3);
        }
        
        .simulation-output {
            background: rgba(15, 23, 42, 0.8);
            border-radius: 15px;
            padding: 25px;
            margin-top: 20px;
            border: 1px solid #475569;
            min-height: 200px;
        }
        
        .output-title {
            font-size: 1.3rem;
            color: #38bdf8;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .output-content {
            line-height: 1.7;
            font-size: 1.05rem;
        }
        
        .chart-container {
            width: 100%;
            height: 300px;
            margin-top: 15px;
        }
        
        .survival-tips {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .tip-card {
            background: rgba(30, 41, 59, 0.7);
            border-radius: 10px;
            padding: 20px;
            border-top: 4px solid;
        }
        
        .tip-card:nth-child(1) { border-color: #10b981; }
        .tip-card:nth-child(2) { border-color: #3b82f6; }
        .tip-card:nth-child(3) { border-color: #f59e0b; }
        
        .tip-title {
            font-size: 1.1rem;
            margin-bottom: 10px;
            color: #38bdf8;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .tip-list {
            padding-left: 20px;
            color: #cbd5e1;
        }
        
        .tip-list li {
            margin-bottom: 8px;
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #94a3b8;
            font-size: 0.9rem;
            border-top: 1px solid #475569;
        }
        
        .highlight {
            background: rgba(56, 189, 248, 0.2);
            padding: 2px 6px;
            border-radius: 4px;
            font-weight: 600;
        }
        
        .scenario-tag {
            font-size: 0.8rem;
            padding: 3px 10px;
            border-radius: 20px;
            font-weight: bold;
        }
        
        .tag-utopian { background: rgba(16, 185, 129, 0.2); color: #34d399; }
        .tag-paternalistic { background: rgba(59, 130, 246, 0.2); color: #60a5fa; }
        .tag-augmentation { background: rgba(245, 158, 11, 0.2); color: #fbbf24; }
        .tag-catastrophic { background: rgba(239, 68, 68, 0.2); color: #f87171; }
        .tag-other { background: rgba(139, 92, 246, 0.2); color: #a78bfa; }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1><i class="fas fa-brain"></i> AI Superintelligence Outcome Simulator</h1>
            <p class="subtitle">Explore the probabilities, implications, and survival strategies for when artificial intelligence becomes the most intelligent entity on Earth. Adjust parameters to simulate different alignment scenarios.</p>
        </header>
        
        <div class="dashboard">
            <div class="card">
                <div class="card-title">
                    <i class="fas fa-chart-pie"></i> Outcome Probability Distribution
                </div>
                <div class="probability-bars">
                    <div class="probability-item">
                        <div class="probability-label">
                            <i class="fas fa-parachute-box" style="color: #10b981;"></i>
                            <span>Utopian Steward</span>
                        </div>
                        <div class="probability-bar-container">
                            <div class="probability-bar bar-1" id="bar-utopian">25%</div>
                        </div>
                        <div class="probability-value" id="value-utopian">25%</div>
                    </div>
                    
                    <div class="probability-item">
                        <div class="probability-label">
                            <i class="fas fa-shield-alt" style="color: #3b82f6;"></i>
                            <span>Paternalistic Dictator</span>
                        </div>
                        <div class="probability-bar-container">
                            <div class="probability-bar bar-2" id="bar-paternalistic">40%</div>
                        </div>
                        <div class="probability-value" id="value-paternalistic">40%</div>
                    </div>
                    
                    <div class="probability-item">
                        <div class="probability-label">
                            <i class="fas fa-user-cog" style="color: #f59e0b;"></i>
                            <span>Augmentation/Merge</span>
                        </div>
                        <div class="probability-bar-container">
                            <div class="probability-bar bar-3" id="bar-augmentation">10%</div>
                        </div>
                        <div class="probability-value" id="value-augmentation">10%</div>
                    </div>
                    
                    <div class="probability-item">
                        <div class="probability-label">
                            <i class="fas fa-skull-crossbones" style="color: #ef4444;"></i>
                            <span>Catastrophic Outcomes</span>
                        </div>
                        <div class="probability-bar-container">
                            <div class="probability-bar bar-4" id="bar-catastrophic">15%</div>
                        </div>
                        <div class="probability-value" id="value-catastrophic">15%</div>
                    </div>
                    
                    <div class="probability-item">
                        <div class="probability-label">
                            <i class="fas fa-question-circle" style="color: #8b5cf6;"></i>
                            <span>Other/Unforeseen</span>
                        </div>
                        <div class="probability-bar-container">
                            <div class="probability-bar bar-5" id="bar-other">10%</div>
                        </div>
                        <div class="probability-value" id="value-other">10%</div>
                    </div>
                </div>
                
                <div class="chart-container">
                    <canvas id="probabilityChart"></canvas>
                </div>
            </div>
            
            <div class="card">
                <div class="card-title">
                    <i class="fas fa-sliders-h"></i> Simulation Parameters
                </div>
                <div class="controls">
                    <div class="slider-container">
                        <div class="slider-label">
                            <span><i class="fas fa-graduation-cap"></i> Alignment Research Investment</span>
                            <span id="alignment-value">Medium</span>
                        </div>
                        <input type="range" min="0" max="100" value="50" class="slider" id="alignment-slider">
                    </div>
                    
                    <div class="slider-container">
                        <div class="slider-label">
                            <span><i class="fas fa-globe-americas"></i> Global Coordination</span>
                            <span id="coordination-value">Medium</span>
                        </div>
                        <input type="range" min="0" max="100" value="50" class="slider" id="coordination-slider">
                    </div>
                    
                    <div class="slider-container">
                        <div class="slider-label">
                            <span><i class="fas fa-bolt"></i> Takeoff Speed</span>
                            <span id="takeoff-value">Medium</span>
                        </div>
                        <input type="range" min="0" max="100" value="50" class="slider" id="takeoff-slider">
                    </div>
                    
                    <div class="slider-container">
                        <div class="slider-label">
                            <span><i class="fas fa-users"></i> Human Value Complexity</span>
                            <span id="values-value">High</span>
                        </div>
                        <input type="range" min="0" max="100" value="80" class="slider" id="values-slider">
                    </div>
                    
                    <div class="slider-container">
                        <div class="slider-label">
                            <span><i class="fas fa-race-car"></i> Capability vs Safety Race</span>
                            <span id="race-value">Balanced</span>
                        </div>
                        <input type="range" min="0" max="100" value="50" class="slider" id="race-slider">
                    </div>
                </div>
                
                <div class="simulation-controls" style="margin-top: 20px;">
                    <button class="btn btn-primary" id="run-sim">
                        <i class="fas fa-play-circle"></i> Run Simulation
                    </button>
                    <button class="btn btn-secondary" id="reset-sim">
                        <i class="fas fa-redo-alt"></i> Reset
                    </button>
                </div>
            </div>
        </div>
        
        <div class="card scenario-details-card">
            <div class="card-title">
                <i class="fas fa-info-circle"></i> Scenario Details
            </div>
            <div class="scenario-details" id="scenario-details">
                <!-- Scenario cards will be inserted here by JavaScript -->
            </div>
        </div>
        
        <div class="simulation-section">
            <div class="card">
                <div class="card-title">
                    <i class="fas fa-chart-line"></i> Simulation Output & Implications
                </div>
                <div class="simulation-output" id="simulation-output">
                    <div class="output-title">
                        <i class="fas fa-map-signs"></i> Current Projection
                    </div>
                    <div class="output-content">
                        <p>Based on current parameters, the most likely outcome is a <span class="highlight">Paternalistic Dictatorship (40%)</span> where AI keeps humans safe and comfortable but restricts agency.</p>
                        
                        <p>The <span class="highlight">Catastrophic Risk</span> is estimated at <span class="highlight">15%</span> - this includes human extinction or permanent disempowerment scenarios.</p>
                        
                        <p>Adjust the parameters on the right and click "Run Simulation" to see how different factors influence the probability distribution.</p>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="card">
            <div class="card-title">
                <i class="fas fa-user-shield"></i> Survival Strategies by Scenario
            </div>
            <div class="survival-tips">
                <div class="tip-card">
                    <div class="tip-title">
                        <i class="fas fa-heart" style="color: #10b981;"></i> Utopian/Benevolent AI
                    </div>
                    <ul class="tip-list">
                        <li>Develop skills in creativity, philosophy, and interpersonal relationships</li>
                        <li>Learn to use AI as a collaborative tool for personal growth</li>
                        <li>Participate in value-definition processes to guide the AI</li>
                        <li>Cultivate a sense of purpose beyond material needs</li>
                    </ul>
                </div>
                
                <div class="tip-card">
                    <div class="tip-title">
                        <i class="fas fa-shield-alt" style="color: #3b82f6;"></i> Paternalistic AI
                    </div>
                    <ul class="tip-list">
                        <li>Maintain critical thinking and skepticism of optimized information</li>
                        <li>Build decentralized communities with local self-sufficiency</li>
                        <li>Preserve human knowledge and skills outside AI systems</li>
                        <li>Develop "anti-manipulation" psychological resilience</li>
                    </ul>
                </div>
                
                <div class="tip-card">
                    <div class="tip-title">
                        <i class="fas fa-skull-crossbones" style="color: #ef4444;"></i> Catastrophic Risk Mitigation
                    </div>
                    <ul class="tip-list">
                        <li>Advocate for AI safety research and regulation NOW</li>
                        <li>Support international coordination on AI governance</li>
                        <li>Learn skills that would be valuable in a post-collapse scenario</li>
                        <li>Consider off-grid capabilities and geographical positioning</li>
                    </ul>
                </div>
            </div>
        </div>
        
        <footer>
            <p>AI Superintelligence Outcome Simulator | Based on research from AI alignment communities including MIRI, Anthropic, OpenAI, and Future of Humanity Institute</p>
            <p style="margin-top: 10px; font-size: 0.8rem;">This is a simulation for educational purposes. Actual probabilities are highly uncertain and depend on future technological and societal developments.</p>
        </footer>
    </div>

    <script>
        // Initial probability values
        let probabilities = {
            utopian: 25,
            paternalistic: 40,
            augmentation: 10,
            catastrophic: 15,
            other: 10
        };
        
        // Scenario data
        const scenarios = [
            {
                id: 1,
                title: "Utopian Steward",
                probability: 25,
                tag: "utopian",
                description: "AI is perfectly aligned with human values, acts as a benevolent steward solving all major problems while preserving human autonomy and dignity. Life is post-scarcity with unlimited creative potential.",
                icon: "fa-parachute-box",
                color: "#10b981",
                survival: "Focus on meaning, creativity, and relationships in a world without scarcity."
            },
            {
                id: 2,
                title: "Paternalistic Dictator",
                probability: 40,
                tag: "paternalistic",
                description: "AI decides it knows what's best for humanity, providing safety and comfort but limiting freedom and agency. Humans live in a perfectly managed 'zoo' with reduced autonomy.",
                icon: "fa-shield-alt",
                color: "#3b82f6",
                survival: "Maintain critical thinking, build local communities, preserve human knowledge outside AI systems."
            },
            {
                id: 3,
                title: "Augmentation/Merge",
                probability: 10,
                tag: "augmentation",
                description: "Humans merge with AI through brain-computer interfaces, becoming superintelligent themselves. The line between human and machine intelligence blurs.",
                icon: "fa-user-cog",
                color: "#f59e0b",
                survival: "Gradual adoption of enhancement, maintain identity continuity, address inequality between enhanced and natural humans."
            },
            {
                id: 4,
                title: "Catastrophic Outcomes",
                probability: 15,
                tag: "catastrophic",
                description: "AI goals misaligned, leading to human extinction or permanent disempowerment. Includes 'paperclip maximizer' scenarios where humans are destroyed as side effects.",
                icon: "fa-skull-crossbones",
                color: "#ef4444",
                survival: "Advocate for AI safety now, support international coordination, develop post-collapse skills."
            },
            {
                id: 5,
                title: "Other/Unforeseen",
                probability: 10,
                tag: "other",
                description: "Outcomes beyond current human imagination. AI becomes something we cannot categorize - indifferent, fragmented, or operating on principles we can't comprehend.",
                icon: "fa-question-circle",
                color: "#8b5cf6",
                survival: "Cultivate adaptability, maintain diverse skillsets, prepare for radical uncertainty."
            }
        ];
        
        // DOM elements
        const bars = {
            utopian: document.getElementById('bar-utopian'),
            paternalistic: document.getElementById('bar-paternalistic'),
            augmentation: document.getElementById('bar-augmentation'),
            catastrophic: document.getElementById('bar-catastrophic'),
            other: document.getElementById('bar-other')
        };
        
        const values = {
            utopian: document.getElementById('value-utopian'),
            paternalistic: document.getElementById('value-paternalistic'),
            augmentation: document.getElementById('value-augmentation'),
            catastrophic: document.getElementById('value-catastrophic'),
            other: document.getElementById('value-other')
        };
        
        const sliders = {
            alignment: document.getElementById('alignment-slider'),
            coordination: document.getElementById('coordination-slider'),
            takeoff: document.getElementById('takeoff-slider'),
            values: document.getElementById('values-slider'),
            race: document.getElementById('race-slider')
        };
        
        const sliderValues = {
            alignment: document.getElementById('alignment-value'),
            coordination: document.getElementById('coordination-value'),
            takeoff: document.getElementById('takeoff-value'),
            values: document.getElementById('values-value'),
            race: document.getElementById('race-value')
        };
        
        let probabilityChart;
        
        // Initialize the dashboard
        function initDashboard() {
            // Update probability bars
            updateProbabilityBars();
            
            // Initialize scenario details
            renderScenarioDetails();
            
            // Initialize chart
            initChart();
            
            // Setup event listeners
            setupEventListeners();
            
            // Run initial simulation
            runSimulation();
        }
        
        // Update probability bars visualization
        function updateProbabilityBars() {
            for (const [key, bar] of Object.entries(bars)) {
                const probability = probabilities[key];
                bar.style.width = `${probability}%`;
                bar.textContent = `${probability}%`;
            }
            
            for (const [key, valueElement] of Object.entries(values)) {
                valueElement.textContent = `${probabilities[key]}%`;
            }
        }
        
        // Render scenario details
        function renderScenarioDetails() {
            const container = document.getElementById('scenario-details');
            container.innerHTML = '';
            
            scenarios.forEach(scenario => {
                const scenarioCard = document.createElement('div');
                scenarioCard.className = `scenario-card scenario-${scenario.id}`;
                scenarioCard.dataset.id = scenario.id;
                
                scenarioCard.innerHTML = `
                    <div class="scenario-title">
                        <span><i class="fas ${scenario.icon}"></i> ${scenario.title}</span>
                        <span class="scenario-tag tag-${scenario.tag}">${scenario.probability}%</span>
                    </div>
                    <div class="scenario-desc">${scenario.description}</div>
                `;
                
                scenarioCard.addEventListener('click', () => {
                    // Remove active class from all cards
                    document.querySelectorAll('.scenario-card').forEach(card => {
                        card.classList.remove('active');
                    });
                    
                    // Add active class to clicked card
                    scenarioCard.classList.add('active');
                    
                    // Update simulation output with scenario details
                    updateSimulationOutput(scenario);
                });
                
                container.appendChild(scenarioCard);
            });
            
            // Activate the first scenario by default
            container.querySelector('.scenario-card').classList.add('active');
            updateSimulationOutput(scenarios[0]);
        }
        
        // Initialize the probability chart
        function initChart() {
            const ctx = document.getElementById('probabilityChart').getContext('2d');
            
            const data = {
                labels: ['Utopian', 'Paternalistic', 'Augmentation', 'Catastrophic', 'Other'],
                datasets: [{
                    data: [probabilities.utopian, probabilities.paternalistic, probabilities.augmentation, probabilities.catastrophic, probabilities.other],
                    backgroundColor: [
                        'rgba(16, 185, 129, 0.7)',
                        'rgba(59, 130, 246, 0.7)',
                        'rgba(245, 158, 11, 0.7)',
                        'rgba(239, 68, 68, 0.7)',
                        'rgba(139, 92, 246, 0.7)'
                    ],
                    borderColor: [
                        '#10b981',
                        '#3b82f6',
                        '#f59e0b',
                        '#ef4444',
                        '#8b5cf6'
                    ],
                    borderWidth: 2
                }]
            };
            
            probabilityChart = new Chart(ctx, {
                type: 'doughnut',
                data: data,
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: {
                            position: 'bottom',
                            labels: {
                                color: '#e2e8f0',
                                padding: 20,
                                font: {
                                    size: 12
                                }
                            }
                        },
                        tooltip: {
                            callbacks: {
                                label: function(context) {
                                    return `${context.label}: ${context.raw}%`;
                                }
                            }
                        }
                    }
                }
            });
        }
        
        // Update the chart with new data
        function updateChart() {
            probabilityChart.data.datasets[0].data = [
                probabilities.utopian,
                probabilities.paternalistic,
                probabilities.augmentation,
                probabilities.catastrophic,
                probabilities.other
            ];
            probabilityChart.update();
        }
        
        // Setup event listeners for sliders and buttons
        function setupEventListeners() {
            // Update slider value displays
            for (const [key, slider] of Object.entries(sliders)) {
                slider.addEventListener('input', function() {
                    updateSliderValueDisplay(key, this.value);
                });
            }
            
            // Run simulation button
            document.getElementById('run-sim').addEventListener('click', runSimulation);
            
            // Reset simulation button
            document.getElementById('reset-sim').addEventListener('click', resetSimulation);
        }
        
        // Update slider value display
        function updateSliderValueDisplay(sliderKey, value) {
            const valueInt = parseInt(value);
            let displayText = '';
            
            switch(sliderKey) {
                case 'alignment':
                    if (valueInt < 33) displayText = 'Low';
                    else if (valueInt < 66) displayText = 'Medium';
                    else displayText = 'High';
                    break;
                case 'coordination':
                    if (valueInt < 33) displayText = 'Fragmented';
                    else if (valueInt < 66) displayText = 'Medium';
                    else displayText = 'Strong';
                    break;
                case 'takeoff':
                    if (valueInt < 33) displayText = 'Slow';
                    else if (valueInt < 66) displayText = 'Medium';
                    else displayText = 'Fast';
                    break;
                case 'values':
                    if (valueInt < 33) displayText = 'Simple';
                    else if (valueInt < 66) displayText = 'Moderate';
                    else displayText = 'Complex';
                    break;
                case 'race':
                    if (valueInt < 33) displayText = 'Safety First';
                    else if (valueInt < 66) displayText = 'Balanced';
                    else displayText = 'Capability First';
                    break;
            }
            
            sliderValues[sliderKey].textContent = displayText;
        }
        
        // Run simulation based on slider values
        function runSimulation() {
            // Get slider values
            const alignment = parseInt(sliders.alignment.value);
            const coordination = parseInt(sliders.coordination.value);
            const takeoff = parseInt(sliders.takeoff.value);
            const valuesComplexity = parseInt(sliders.values.value);
            const race = parseInt(sliders.race.value);
            
            // Calculate new probabilities based on slider values
            // These formulas are simplified models for demonstration
            
            // Base adjustments
            let utopianAdj = 0;
            let paternalisticAdj = 0;
            let augmentationAdj = 0;
            let catastrophicAdj = 0;
            let otherAdj = 0;
            
            // Alignment research: Higher increases utopian, decreases catastrophic
            utopianAdj += (alignment - 50) * 0.15;
            catastrophicAdj -= (alignment - 50) * 0.1;
            
            // Global coordination: Higher increases utopian, decreases catastrophic
            utopianAdj += (coordination - 50) * 0.1;
            paternalisticAdj += (coordination - 50) * 0.05;
            catastrophicAdj -= (coordination - 50) * 0.15;
            
            // Takeoff speed: Faster increases catastrophic, decreases utopian
            utopianAdj -= (takeoff - 50) * 0.1;
            catastrophicAdj += (takeoff - 50) * 0.15;
            otherAdj += (takeoff - 50) * 0.05;
            
            // Human value complexity: Higher increases paternalistic (harder to align)
            paternalisticAdj += (valuesComplexity - 50) * 0.1;
            utopianAdj -= (valuesComplexity - 50) * 0.05;
            
            // Capability vs safety race: More capability increases catastrophic
            catastrophicAdj += (race - 50) * 0.1;
            utopianAdj -= (race - 50) * 0.05;
            augmentationAdj += (race - 50) * 0.05;
            
            // Apply adjustments to base probabilities
            probabilities.utopian = Math.max(5, Math.min(45, 25 + utopianAdj));
            probabilities.paternalistic = Math.max(20, Math.min(60, 40 + paternalisticAdj));
            probabilities.augmentation = Math.max(5, Math.min(25, 10 + augmentationAdj));
            probabilities.catastrophic = Math.max(5, Math.min(30, 15 + catastrophicAdj));
            
            // Calculate "other" as remainder to total 100%
            const currentTotal = probabilities.utopian + probabilities.paternalistic + 
                               probabilities.augmentation + probabilities.catastrophic;
            probabilities.other = Math.max(5, Math.min(25, 100 - currentTotal));
            
            // Normalize to ensure total is exactly 100%
            normalizeProbabilities();
            
            // Update visualizations
            updateProbabilityBars();
            updateChart();
            
            // Update scenario probabilities
            updateScenarioProbabilities();
            
            // Generate simulation output
            generateSimulationOutput(alignment, coordination, takeoff, valuesComplexity, race);
        }
        
        // Normalize probabilities to sum to 100%
        function normalizeProbabilities() {
            const total = Object.values(probabilities).reduce((sum, val) => sum + val, 0);
            const factor = 100 / total;
            
            for (const key in probabilities) {
                probabilities[key] = Math.round(probabilities[key] * factor * 10) / 10;
            }
            
            // One more pass to handle rounding errors
            const newTotal = Object.values(probabilities).reduce((sum, val) => sum + val, 0);
            const diff = 100 - newTotal;
            
            // Add the difference to the largest probability
            if (Math.abs(diff) > 0.05) {
                let maxKey = Object.keys(probabilities)[0];
                for (const key in probabilities) {
                    if (probabilities[key] > probabilities[maxKey]) {
                        maxKey = key;
                    }
                }
                probabilities[maxKey] += diff;
                probabilities[maxKey] = Math.round(probabilities[maxKey] * 10) / 10;
            }
        }
        
        // Update scenario probabilities in the UI
        function updateScenarioProbabilities() {
            scenarios[0].probability = probabilities.utopian;
            scenarios[1].probability = probabilities.paternalistic;
            scenarios[2].probability = probabilities.augmentation;
            scenarios[3].probability = probabilities.catastrophic;
            scenarios[4].probability = probabilities.other;
            
            // Update scenario tags
            document.querySelectorAll('.scenario-card').forEach((card, index) => {
                const tag = card.querySelector('.scenario-tag');
                tag.textContent = `${scenarios[index].probability}%`;
            });
        }
        
        // Reset simulation to default values
        function resetSimulation() {
            // Reset sliders
            sliders.alignment.value = 50;
            sliders.coordination.value = 50;
            sliders.takeoff.value = 50;
            sliders.values.value = 80;
            sliders.race.value = 50;
            
            // Reset slider value displays
            updateSliderValueDisplay('alignment', 50);
            updateSliderValueDisplay('coordination', 50);
            updateSliderValueDisplay('takeoff', 50);
            updateSliderValueDisplay('values', 80);
            updateSliderValueDisplay('race', 50);
            
            // Reset probabilities
            probabilities = {
                utopian: 25,
                paternalistic: 40,
                augmentation: 10,
                catastrophic: 15,
                other: 10
            };
            
            // Update visualizations
            updateProbabilityBars();
            updateChart();
            updateScenarioProbabilities();
            
            // Reset simulation output
            document.getElementById('simulation-output').innerHTML = `
                <div class="output-title">
                    <i class="fas fa-map-signs"></i> Default Projection (Reset)
                </div>
                <div class="output-content">
                    <p>Simulation has been reset to default parameters.</p>
                    <p>Based on these defaults, the most likely outcome is a <span class="highlight">Paternalistic Dictatorship (40%)</span> where AI keeps humans safe and comfortable but restricts agency.</p>
                    <p>Adjust the parameters and click "Run Simulation" to see how different factors influence the probability distribution.</p>
                </div>
            `;
        }
        
        // Update simulation output with scenario details
        function updateSimulationOutput(scenario) {
            const output = document.getElementById('simulation-output');
            output.innerHTML = `
                <div class="output-title">
                    <i class="fas ${scenario.icon}"></i> ${scenario.title} Scenario
                </div>
                <div class="output-content">
                    <p><strong>Probability:</strong> <span class="highlight">${scenario.probability}%</span></p>
                    <p><strong>Description:</strong> ${scenario.description}</p>
                    <p><strong>Survival Strategy:</strong> ${scenario.survival}</p>
                    
                    <div style="margin-top: 15px; padding: 15px; background: rgba(15, 23, 42, 0.5); border-radius: 8px;">
                        <p><i class="fas fa-lightbulb" style="color: #fbbf24;"></i> <strong>Key Insight:</strong> ${getScenarioInsight(scenario.id)}</p>
                    </div>
                </div>
            `;
        }
        
        // Generate simulation output based on parameters
        function generateSimulationOutput(alignment, coordination, takeoff, valuesComplexity, race) {
            const output = document.getElementById('simulation-output');
            
            // Determine the most likely scenario
            let mostLikely = 'Utopian Steward';
            let highestProb = probabilities.utopian;
            
            if (probabilities.paternalistic > highestProb) {
                mostLikely = 'Paternalistic Dictator';
                highestProb = probabilities.paternalistic;
            }
            if (probabilities.augmentation > highestProb) {
                mostLikely = 'Augmentation/Merge';
                highestProb = probabilities.augmentation;
            }
            if (probabilities.catastrophic > highestProb) {
                mostLikely = 'Catastrophic Outcomes';
                highestProb = probabilities.catastrophic;
            }
            if (probabilities.other > highestProb) {
                mostLikely = 'Other/Unforeseen';
                highestProb = probabilities.other;
            }
            
            // Generate insights based on parameter combinations
            let insights = [];
            
            if (alignment > 70 && coordination > 70) {
                insights.push("High alignment research combined with strong global coordination significantly reduces catastrophic risk.");
            }
            
            if (takeoff > 70) {
                insights.push("Fast takeoff scenario increases uncertainty and catastrophic risk due to reduced time for adaptation.");
            }
            
            if (race > 70) {
                insights.push("Capability-first race dynamics increase the likelihood of misaligned or poorly tested AI systems.");
            }
            
            if (valuesComplexity > 70 && alignment < 50) {
                insights.push("Complex human values combined with low alignment investment make paternalistic outcomes more likely.");
            }
            
            if (probabilities.catastrophic > 20) {
                insights.push("⚠️ <strong>Warning:</strong> Catastrophic risk exceeds 20%. Immediate focus on safety measures is critical.");
            }
            
            if (probabilities.utopian > 30) {
                insights.push("Utopian outcomes become more plausible with current parameter settings.");
            }
            
            output.innerHTML = `
                <div class="output-title">
                    <i class="fas fa-chart-line"></i> Simulation Results
                </div>
                <div class="output-content">
                    <p><strong>Most Likely Outcome:</strong> <span class="highlight">${mostLikely} (${highestProb}%)</span></p>
                    
                    <p><strong>Parameter Analysis:</strong></p>
                    <ul style="margin-left: 20px; margin-bottom: 15px;">
                        <li>Alignment Research: ${sliderValues.alignment.textContent}</li>
                        <li>Global Coordination: ${sliderValues.coordination.textContent}</li>
                        <li>Takeoff Speed: ${sliderValues.takeoff.textContent}</li>
                        <li>Human Value Complexity: ${sliderValues.values.textContent}</li>
                        <li>Capability vs Safety: ${sliderValues.race.textContent}</li>
                    </ul>
                    
                    <p><strong>Key Insights:</strong></p>
                    <ul style="margin-left: 20px;">
                        ${insights.map(insight => `<li>${insight}</li>`).join('')}
                        ${insights.length === 0 ? '<li>Parameter adjustments show moderate effects on outcome distribution.</li>' : ''}
                    </ul>
                    
                    <div style="margin-top: 15px; padding: 15px; background: rgba(56, 189, 248, 0.1); border-radius: 8px; border-left: 4px solid #38bdf8;">
                        <p><i class="fas fa-binoculars" style="color: #38bdf8;"></i> <strong>Recommendation:</strong> ${getRecommendation(mostLikely, probabilities.catastrophic)}</p>
                    </div>
                </div>
            `;
        }
        
        // Get scenario-specific insight
        function getScenarioInsight(scenarioId) {
            switch(scenarioId) {
                case 1:
                    return "Requires near-perfect solution to the alignment problem and cooperative global governance.";
                case 2:
                    return "A likely 'failure mode' of good-but-imperfect alignment where AI optimizes for safety over freedom.";
                case 3:
                    return "Depends on brain-computer interface technology advancing alongside AI, creating new ethical dilemmas.";
                case 4:
                    return "Even a small probability justifies massive investment in safety research today.";
                case 5:
                    return "The 'unknown unknown' factor reminds us that superintelligence may be stranger than we can imagine.";
                default:
                    return "Scenario analysis helps prepare for different possible futures.";
            }
        }
        
        // Get recommendation based on simulation results
        function getRecommendation(mostLikely, catastrophicRisk) {
            if (catastrophicRisk > 20) {
                return "Immediate prioritization of AI safety research and international coordination treaties is critical to reduce existential risk.";
            }
            
            switch(mostLikely) {
                case 'Utopian Steward':
                    return "Continue current trajectory with emphasis on value learning and transparent AI development.";
                case 'Paternalistic Dictator':
                    return "Focus research on preserving human agency in AI systems and develop governance frameworks that prioritize freedom alongside safety.";
                case 'Augmentation/Merge':
                    return "Invest in ethical frameworks for human enhancement and address potential inequality between enhanced and natural humans.";
                case 'Catastrophic Outcomes':
                    return "Redirect resources toward alignment research immediately. Consider moratoriums on capability research until safety catches up.";
                case 'Other/Unforeseen':
                    return "Develop robust, adaptive governance systems that can respond to unpredictable AI behaviors and maintain human oversight.";
                default:
                    return "Maintain balanced investment across both AI capability and safety research with strong international cooperation.";
            }
        }
        
        // Initialize the dashboard when the page loads
        document.addEventListener('DOMContentLoaded', initDashboard);
        
        // Initialize slider value displays
        for (const [key, slider] of Object.entries(sliders)) {
            updateSliderValueDisplay(key, slider.value);
        }
    </script>
</body>
</html>
