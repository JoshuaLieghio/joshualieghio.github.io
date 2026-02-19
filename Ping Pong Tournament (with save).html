<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ping Pong Tournament Tracker</title>
    <style>
        :root {
            --color-bg-primary: #f8fafc;
            --color-bg-secondary: #ffffff;
            --color-text-primary: #0f172a;
            --color-text-secondary: #475569;
            --color-border: #e2e8f0;
            --color-primary: #0284c7;
            --color-primary-hover: #0369a1;
            --color-success: #22c55e;
            --color-warning: #f59e0b;
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --color-bg-primary: #0f172a;
                --color-bg-secondary: #1e293b;
                --color-text-primary: #f1f5f9;
                --color-text-secondary: #cbd5e1;
                --color-border: #334155;
                --color-primary: #38bdf8;
                --color-primary-hover: #7dd3fc;
            }
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: var(--color-bg-primary);
            color: var(--color-text-primary);
            padding: 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
        }

        h1 {
            font-size: 2rem;
            margin-bottom: 10px;
            color: var(--color-text-primary);
        }

        .subtitle {
            color: var(--color-text-secondary);
            margin-bottom: 30px;
            font-size: 0.95rem;
        }

        .tabs {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
            border-bottom: 2px solid var(--color-border);
        }

        .tab {
            padding: 12px 24px;
            background: none;
            border: none;
            border-bottom: 3px solid transparent;
            color: var(--color-text-secondary);
            cursor: pointer;
            font-size: 1rem;
            font-weight: 500;
            transition: all 0.2s;
        }

        .tab:hover {
            color: var(--color-text-primary);
        }

        .tab.active {
            color: var(--color-primary);
            border-bottom-color: var(--color-primary);
        }

        .tab-content {
            display: none;
        }

        .tab-content.active {
            display: block;
        }

        .card {
            background: var(--color-bg-secondary);
            border-radius: 12px;
            padding: 24px;
            box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        .table-container {
            overflow-x: auto;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.9rem;
        }

        th {
            background: var(--color-bg-primary);
            color: var(--color-text-primary);
            font-weight: 600;
            text-align: left;
            padding: 12px;
            border-bottom: 2px solid var(--color-border);
            position: sticky;
            top: 0;
        }

        td {
            padding: 12px;
            border-bottom: 1px solid var(--color-border);
        }

        tr:hover {
            background: var(--color-bg-primary);
        }

        input[type="number"] {
            width: 70px;
            padding: 6px 8px;
            border: 1px solid var(--color-border);
            border-radius: 6px;
            background: var(--color-bg-primary);
            color: var(--color-text-primary);
            font-size: 0.9rem;
        }

        input[type="number"]:focus {
            outline: 2px solid var(--color-primary);
            outline-offset: 1px;
        }

        .winner-display {
            font-weight: 600;
            color: var(--color-success);
        }

        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 16px;
            margin-bottom: 20px;
        }

        .stat-card {
            background: var(--color-bg-primary);
            padding: 16px;
            border-radius: 8px;
            text-align: center;
        }

        .stat-value {
            font-size: 2rem;
            font-weight: 700;
            color: var(--color-primary);
            margin-bottom: 4px;
        }

        .stat-label {
            font-size: 0.85rem;
            color: var(--color-text-secondary);
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .rank-badge {
            display: inline-block;
            width: 28px;
            height: 28px;
            line-height: 28px;
            text-align: center;
            border-radius: 50%;
            font-weight: 700;
            font-size: 0.85rem;
            background: var(--color-bg-primary);
            color: var(--color-text-primary);
            margin-right: 8px;
        }

        .rank-1 {
            background: #fbbf24;
            color: #78350f;
        }

        .rank-2 {
            background: #94a3b8;
            color: #1e293b;
        }

        .rank-3 {
            background: #fb923c;
            color: #7c2d12;
        }

        .positive {
            color: var(--color-success);
        }

        .negative {
            color: #ef4444;
        }

        .match-number {
            font-weight: 600;
            color: var(--color-text-secondary);
        }

        .vs {
            color: var(--color-text-secondary);
            font-weight: 600;
            padding: 0 8px;
        }

        .reset-btn {
            padding: 10px 20px;
            background: #ef4444;
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 0.9rem;
            font-weight: 600;
            transition: background 0.2s;
            margin-top: 10px;
        }

        .reset-btn:hover {
            background: #dc2626;
        }

        .export-btn, .import-btn {
            padding: 10px 20px;
            background: var(--color-primary);
            color: white;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 0.9rem;
            font-weight: 600;
            transition: background 0.2s;
            margin-top: 10px;
        }

        .export-btn:hover, .import-btn:hover {
            background: var(--color-primary-hover);
        }

        @media (max-width: 768px) {
            body {
                padding: 10px;
            }

            h1 {
                font-size: 1.5rem;
            }

            .tabs {
                overflow-x: auto;
            }

            table {
                font-size: 0.8rem;
            }

            th, td {
                padding: 8px;
            }

            input[type="number"] {
                width: 60px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🏓 Ping Pong Tournament Tracker</h1>
        <p class="subtitle">Round Robin Tournament - 9 Players, 36 Matches</p>

        <div class="tabs">
            <button class="tab active" onclick="switchTab('matches')">Match Schedule</button>
            <button class="tab" onclick="switchTab('standings')">Player Standings</button>
        </div>

        <div id="matches" class="tab-content active">
            <div class="stats-grid">
                <div class="stat-card">
                    <div class="stat-value" id="completedMatches">0</div>
                    <div class="stat-label">Completed</div>
                </div>
                <div class="stat-card">
                    <div class="stat-value" id="remainingMatches">36</div>
                    <div class="stat-label">Remaining</div>
                </div>
                <div class="stat-card">
                    <div class="stat-value" id="totalPoints">0</div>
                    <div class="stat-label">Total Points</div>
                </div>
            </div>

            <div class="card">
                <div class="table-container">
                    <table id="matchTable">
                        <thead>
                            <tr>
                                <th>Match</th>
                                <th>Player 1</th>
                                <th>Score</th>
                                <th></th>
                                <th>Score</th>
                                <th>Player 2</th>
                                <th>Winner</th>
                            </tr>
                        </thead>
                        <tbody id="matchTableBody"></tbody>
                    </table>
                </div>
            </div>

            <div style="display: flex; gap: 10px; margin-top: 10px; flex-wrap: wrap;">
                <button class="reset-btn" onclick="resetAllMatches()">Reset All Matches</button>
                <button class="export-btn" onclick="exportData()">📥 Export Data</button>
                <button class="import-btn" onclick="document.getElementById('importFile').click()">📤 Import Data</button>
                <input type="file" id="importFile" accept=".json" style="display: none;" onchange="importData(event)">
            </div>
        </div>

        <div id="standings" class="tab-content">
            <div class="card">
                <div class="table-container">
                    <table id="standingsTable">
                        <thead>
                            <tr>
                                <th>Rank</th>
                                <th>Player</th>
                                <th>Played</th>
                                <th>Wins</th>
                                <th>Losses</th>
                                <th>Points For</th>
                                <th>Points Against</th>
                                <th>Diff</th>
                            </tr>
                        </thead>
                        <tbody id="standingsTableBody"></tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>

    <script>
        const players = ['Cathy', 'Conor', 'Eoin', 'Joshua', 'Karl', 'Michael', 'Remi', 'Robert', 'Ryan'];
        
        const matches = [
            ['Cathy', 'Conor'], ['Cathy', 'Eoin'], ['Cathy', 'Joshua'], ['Cathy', 'Karl'],
            ['Cathy', 'Michael'], ['Cathy', 'Remi'], ['Cathy', 'Robert'], ['Cathy', 'Ryan'],
            ['Conor', 'Eoin'], ['Conor', 'Joshua'], ['Conor', 'Karl'], ['Conor', 'Michael'],
            ['Conor', 'Remi'], ['Conor', 'Robert'], ['Conor', 'Ryan'], ['Eoin', 'Joshua'],
            ['Eoin', 'Karl'], ['Eoin', 'Michael'], ['Eoin', 'Remi'], ['Eoin', 'Robert'],
            ['Eoin', 'Ryan'], ['Joshua', 'Karl'], ['Joshua', 'Michael'], ['Joshua', 'Remi'],
            ['Joshua', 'Robert'], ['Joshua', 'Ryan'], ['Karl', 'Michael'], ['Karl', 'Remi'],
            ['Karl', 'Robert'], ['Karl', 'Ryan'], ['Michael', 'Remi'], ['Michael', 'Robert'],
            ['Michael', 'Ryan'], ['Remi', 'Robert'], ['Remi', 'Ryan'], ['Robert', 'Ryan']
        ];

        let matchResults = {};

        function initializeMatchTable() {
            const tbody = document.getElementById('matchTableBody');
            tbody.innerHTML = '';

            matches.forEach((match, index) => {
                const row = document.createElement('tr');
                const matchNum = index + 1;
                const result = matchResults[matchNum] || { score1: '', score2: '' };

                row.innerHTML = `
                    <td class="match-number">#${matchNum}</td>
                    <td><strong>${match[0]}</strong></td>
                    <td><input type="number" id="score1-${matchNum}" value="${result.score1}" min="0" onchange="updateMatch(${matchNum})"></td>
                    <td class="vs">vs</td>
                    <td><input type="number" id="score2-${matchNum}" value="${result.score2}" min="0" onchange="updateMatch(${matchNum})"></td>
                    <td><strong>${match[1]}</strong></td>
                    <td id="winner-${matchNum}" class="winner-display"></td>
                `;
                tbody.appendChild(row);
            });

            updateAllWinners();
        }

        function updateMatch(matchNum) {
            const score1 = document.getElementById(`score1-${matchNum}`).value;
            const score2 = document.getElementById(`score2-${matchNum}`).value;

            if (score1 !== '' && score2 !== '') {
                matchResults[matchNum] = {
                    score1: parseInt(score1),
                    score2: parseInt(score2)
                };
            } else {
                delete matchResults[matchNum];
            }

            updateAllWinners();
            updateStandings();
            updateStats();
        }

        function updateAllWinners() {
            matches.forEach((match, index) => {
                const matchNum = index + 1;
                const winnerCell = document.getElementById(`winner-${matchNum}`);
                const result = matchResults[matchNum];

                if (result) {
                    if (result.score1 > result.score2) {
                        winnerCell.textContent = match[0];
                    } else if (result.score2 > result.score1) {
                        winnerCell.textContent = match[1];
                    } else {
                        winnerCell.textContent = 'Draw';
                    }
                } else {
                    winnerCell.textContent = '';
                }
            });
        }

        function calculateStandings() {
            const standings = {};

            players.forEach(player => {
                standings[player] = {
                    played: 0,
                    wins: 0,
                    losses: 0,
                    pointsFor: 0,
                    pointsAgainst: 0
                };
            });

            matches.forEach((match, index) => {
                const matchNum = index + 1;
                const result = matchResults[matchNum];

                if (result) {
                    const [player1, player2] = match;
                    const { score1, score2 } = result;

                    standings[player1].played++;
                    standings[player2].played++;
                    standings[player1].pointsFor += score1;
                    standings[player1].pointsAgainst += score2;
                    standings[player2].pointsFor += score2;
                    standings[player2].pointsAgainst += score1;

                    if (score1 > score2) {
                        standings[player1].wins++;
                        standings[player2].losses++;
                    } else if (score2 > score1) {
                        standings[player2].wins++;
                        standings[player1].losses++;
                    }
                }
            });

            return Object.entries(standings).map(([player, stats]) => ({
                player,
                ...stats,
                diff: stats.pointsFor - stats.pointsAgainst
            })).sort((a, b) => {
                if (b.wins !== a.wins) return b.wins - a.wins;
                if (b.diff !== a.diff) return b.diff - a.diff;
                return b.pointsFor - a.pointsFor;
            });
        }

        function updateStandings() {
            const standings = calculateStandings();
            const tbody = document.getElementById('standingsTableBody');
            tbody.innerHTML = '';

            standings.forEach((player, index) => {
                const row = document.createElement('tr');
                const rank = index + 1;
                let rankClass = '';
                if (rank === 1) rankClass = 'rank-1';
                else if (rank === 2) rankClass = 'rank-2';
                else if (rank === 3) rankClass = 'rank-3';

                const diffClass = player.diff > 0 ? 'positive' : player.diff < 0 ? 'negative' : '';

                row.innerHTML = `
                    <td><span class="rank-badge ${rankClass}">${rank}</span></td>
                    <td><strong>${player.player}</strong></td>
                    <td>${player.played}</td>
                    <td>${player.wins}</td>
                    <td>${player.losses}</td>
                    <td>${player.pointsFor}</td>
                    <td>${player.pointsAgainst}</td>
                    <td class="${diffClass}">${player.diff > 0 ? '+' : ''}${player.diff}</td>
                `;
                tbody.appendChild(row);
            });
        }

        function updateStats() {
            const completed = Object.keys(matchResults).length;
            const remaining = 36 - completed;
            const totalPoints = Object.values(matchResults).reduce((sum, result) => 
                sum + result.score1 + result.score2, 0);

            document.getElementById('completedMatches').textContent = completed;
            document.getElementById('remainingMatches').textContent = remaining;
            document.getElementById('totalPoints').textContent = totalPoints;
        }

        function switchTab(tabName) {
            document.querySelectorAll('.tab').forEach(tab => tab.classList.remove('active'));
            document.querySelectorAll('.tab-content').forEach(content => content.classList.remove('active'));
            
            event.target.classList.add('active');
            document.getElementById(tabName).classList.add('active');
        }

        function resetAllMatches() {
            if (confirm('Are you sure you want to reset all match results? This cannot be undone.')) {
                matchResults = {};
                initializeMatchTable();
                updateStandings();
                updateStats();
            }
        }

        function exportData() {
            const exportData = {
                version: '1.0',
                date: new Date().toISOString(),
                matches: matches,
                matchResults: matchResults
            };

            const dataStr = JSON.stringify(exportData, null, 2);
            const dataBlob = new Blob([dataStr], { type: 'application/json' });
            const url = URL.createObjectURL(dataBlob);
            
            const link = document.createElement('a');
            link.href = url;
            link.download = `ping-pong-tournament-${new Date().toISOString().split('T')[0]}.json`;
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);
            URL.revokeObjectURL(url);
        }

        function importData(event) {
            const file = event.target.files[0];
            if (!file) return;

            const reader = new FileReader();
            reader.onload = function(e) {
                try {
                    const importedData = JSON.parse(e.target.result);
                    
                    if (!importedData.matchResults) {
                        alert('Invalid file format. Please select a valid tournament data file.');
                        return;
                    }

                    if (Object.keys(matchResults).length > 0) {
                        if (!confirm('This will replace all current match results. Continue?')) {
                            return;
                        }
                    }

                    matchResults = importedData.matchResults;
                    initializeMatchTable();
                    updateStandings();
                    updateStats();
                    
                    alert('Tournament data imported successfully!');
                } catch (error) {
                    alert('Error reading file. Please make sure it is a valid JSON file.');
                    console.error(error);
                }
            };
            reader.readAsText(file);
            
            event.target.value = '';
        }

        initializeMatchTable();
        updateStandings();
        updateStats();
    </script>
</body>
</html>
