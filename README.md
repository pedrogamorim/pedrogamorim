## Hi there!👋 Eu sou o Pedro Gabriel!

- 🔭 I’m currently working administration
- 🌱 I’m currently learning Spring Boot
- 📫 How reach me: amorimjeronimo.gabriel@outlook.com
- 😄 Pronouns: ele/dele


<!-- Ícones das linguagens com URLs originais -->
<div style="display: inline_block; margin-bottom: 20px;">
  <img align="center" alt="Java-pedro" height="30" width="40" src="https://img.shields.io/badge/Java-orange.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAAOxAAADsQBlSsOGwAAAxxJREFUWIXF112IlGUUB/Dfrlumsju2gboRRRsZGJGkJGhYF0VEFBaBIAVFYRdB3ZVIdCOoXUiI6IUIgnhjhVIUEllREEUQUtGHBZLaF+ZX6brmTjtdnDPOu9OOOzPs6B9e3neeeZ/zP895zvmf52XyMLedSd2T6MAzk2irZQzgNLouB3kP3sOJy0E+FW+igu2XmnwOPk3yv3BD4b8S7sL0TpHfiV+SvIxlmIEX8AW+w6JOkT+Ms0n+L57Gffg1x3bo4MqX4p8C+UoswTmM4pVOEVfxfZJX8FKOVfNgR6fJSwXyD3LsCpEDFTzVjtFWlPBv/J7Pu/Jexpl8frQdB6a0+H63SLifsTfHqiV3Mz7E4XYcaRY9+ETUfSnHpqnlxu5OklfRj/14uTD2UDrwWavG2umGJ3AP7sCsHDuY99fbsNcQs/Cc0Ph9WJ2kVad7cFs+v4a1xnbDbqzA1/gWT4xH0qh9zhH7OjN/v4EtYvVnheh0iWbUjxsxlPOuxQg2iAoZwMcYFIeWarQuiquwUyhcpcmrjJ+wUfSFItbnO8uajUAV00WYF6b3R0RoR0QkTuGoaEyHcL6Bnfdxr9jC/RNw/g8rRHi3qSVdEV24Ho+IY1lP3f/3iy37qFXiKtalgUre/8SP+EFEpH6b3hFbCPNF3uzDNeMZb/YMNw8P4Hax2pJY6TkcF8r4jWhMX6UjC0WrfltNNdvGoFDArWqrk04M4jFsEns8KRjA3UJwevGqsdl+XCRg2djwj4hcqEfTp+XZ4oQ7miQbxOpKeFHs5WFR38M4JkRmD1bh1gZ23xWaMSHWqK1mTbNeXwRXiuiVRVQnxC34TS3j9wo5XoSrm5g/VSTscmwW54chPFt4p684Yby9KeWE5aKMig3rjAj7aVEBRCL2poP9aXMEX4oK2I4/0rlVQuIvNK2JkqMkSm8urhO1PFOEdkoSDeOkmiIeEHkxnDZm43E8j7fyfgH1qlWPISE8fbnygyIJTzV4v1d8oDyIBaKSFggVfNI4atjKx+QAFguBuUlEo09EaUZeoyISR0QUPhfHtKONjP4HxJ7K18iRRpEAAAAASUVORK5CYII=">
  
  <img align="center" alt="Pedro-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  
  <img align="center" alt="Pedro-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
</div>

<!-- Gráfico circular com legenda -->
<h4 style="margin-top: 40px;">Analisador de Linguagens</h4>

<canvas id="languageChart" width="300" height="300"></canvas>

<ul style="list-style: none; padding-left: 0; margin-top: 20px;">
  <li><span style="display: inline-block; width: 12px; height: 12px; background: orange; margin-right: 8px;"></span>Java - 50%</li>
  <li><span style="display: inline-block; width: 12px; height: 12px; background: #264de4; margin-right: 8px;"></span>CSS3 - 30%</li>
  <li><span style="display: inline-block; width: 12px; height: 12px; background: #e34c26; margin-right: 8px;"></span>HTML5 - 20%</li>
</ul>

<!-- Script para gerar o gráfico circular com Chart.js -->
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
  const ctx = document.getElementById('languageChart').getContext('2d');
  new Chart(ctx, {
    type: 'doughnut',
    data: {
      labels: ['Java', 'CSS3', 'HTML5'],
      datasets: [{
        data: [50, 30, 20],
        backgroundColor: ['orange', '#264de4', '#e34c26'],
        borderWidth: 1
      }]
    },
    options: {
      plugins: {
        legend: {
          display: false
        }
      }
    }
  });
</script>
