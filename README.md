# Развертывание сайта omnifood в github
<style>
.gradient-table {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 12px;
  padding: 20px;
  color: white;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
}
.gradient-table table {
  width: 100%;
  border-collapse: collapse;
  background: rgba(255,255,255,0.1);
  backdrop-filter: blur(10px);
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 8px 32px rgba(0,0,0,0.3);
}
.gradient-table th, .gradient-table td {
  padding: 12px 16px;
  text-align: left;
  border-bottom: 1px solid rgba(255,255,255,0.2);
}
.gradient-table th {
  background: rgba(255,255,255,0.2);
  font-weight: 600;
  text-transform: uppercase;
  font-size: 0.85em;
  letter-spacing: 0.5px;
}
.gradient-table tr:hover {
  background: rgba(255,255,255,0.15);
  transform: scale(1.01);
  transition: all 0.2s ease;
}
.metric-good { color: #4ade80; font-weight: bold; }
.metric-excellent { color: #fbbf24; font-weight: bold; }
</style>

<div class="gradient-table">
<table>
  <thead>
    <tr>
      <th>Метрика</th>
      <th>До оптимизации</th>
      <th>Цель</th>
      <th>✅ Статус</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Performance Score</strong></td>
      <td><span class="metric-excellent">100</span></td>
      <td>> 90</td>
      <td><span style="color: #10b981;">✅ Превышает</span></td>
    </tr>
    <tr>
      <td><strong>FCP</strong></td>
      <td><span class="metric-excellent">0.6s</span></td>
      <td>< 1.8s</td>
      <td><span style="color: #10b981;">✅ Отлично</span></td>
    </tr>
    <tr>
      <td><strong>LCP</strong></td>
      <td><span class="metric-excellent">0.6s</span></td>
      <td>< 2.5s</td>
      <td><span style="color: #10b981;">✅ Отлично</span></td>
    </tr>
    <tr>
      <td><strong>CLS</strong></td>
      <td><span class="metric-good">0.005</span></td>
      <td>< 0.1</td>
      <td><span style="color: #10b981;">✅ Идеально</span></td>
    </tr>
    <tr>
      <td><strong>TBT</strong></td>
      <td><span class="metric-excellent">0s</span></td>
      <td>< 200ms</td>
      <td><span style="color: #10b981;">✅ Совершенно</span></td>
    </tr>
  </tbody>
</table>
<div style="text-align: center; margin-top: 16px; font-size: 0.9em; opacity: 0.9;">
  🎉 Все метрики превосходят цели! Идеальная производительность сайта.
</div>
</div>
