# Requisitos identificados


<table border="1" style="border-collapse: collapse; width: 100%; font-family: Arial, sans-serif;">
  <thead>
    <tr style="background-color: #f2f2f2; font-weight: bold;">
      <th style="padding: 12px; text-align: left;">ID</th>
      <th style="padding: 12px; text-align: left;">Tipo</th>
      <th style="padding: 12px; text-align: left;">Descrição</th>
      <th style="padding: 12px; text-align: center;">Prioridade</th>
      <th style="padding: 12px; text-align: left;">Fonte</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 10px;"><code>RF-001</code></td>
      <td style="padding: 10px; background-color: #d4edda; font-weight: bold;">RF</td>
      <td style="padding: 10px;">Lançamento de notas em lote por turma (selecionar múltiplos alunos).</td>
      <td style="padding: 10px; text-align: center; background-color: #fff3cd;">Must</td>
      <td style="padding: 10px;">Processo Atual Q1; Entrevista1.md</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><code>RF-002</code></td>
      <td style="padding: 10px; background-color: #d4edda; font-weight: bold;">RF</td>
      <td style="padding: 10px;">Upload de gabarito para correção automática de provas (ex.: múltipla escolha).</td>
      <td style="padding: 10px; text-align: center; background-color: #fff3cd;">Must</td>
      <td style="padding: 10px;">Processo Atual Q3; Entrevista2.md</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><code>RF-003</code></td>
      <td style="padding: 10px; background-color: #d4edda; font-weight: bold;">RF</td>
      <td style="padding: 10px;">Notificações push/email automáticas aos alunos após lançamento de notas.</td>
      <td style="padding: 10px; text-align: center; background-color: #d1ecf1;">Should</td>
      <td style="padding: 10px;">Validação Q1; Entrevista1.md</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><code>RF-004</code></td>
      <td style="padding: 10px; background-color: #d4edda; font-weight: bold;">RF</td>
      <td style="padding: 10px;">Controle de frequência integrado (importar planilhas ou app).</td>
      <td style="padding: 10px; text-align: center; background-color: #d1ecf1;">Should</td>
      <td style="padding: 10px;">Processo Atual Q2; Entrevista1.md</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><code>RNF-001</code></td>
      <td style="padding: 10px; background-color: #d1ecf1; font-weight: bold;">RNF</td>
      <td style="padding: 10px;">Tempo de resposta ≤5s para lançamento de nota (evitar lentidão).</td>
      <td style="padding: 10px; text-align: center; background-color: #fff3cd;">Must</td>
      <td style="padding: 10px;">Necessidades Q5; Entrevista2.md</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><code>RNF-002</code></td>
      <td style="padding: 10px; background-color: #d1ecf1; font-weight: bold;">RNF</td>
      <td style="padding: 10px;">Interface responsiva para mobile/tablet (acesso remoto).</td>
      <td style="padding: 10px; text-align: center; background-color: #fff3cd;">Must</td>
      <td style="padding: 10px;">Necessidades Q4; Entrevista1.md</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><code>RNF-003</code></td>
      <td style="padding: 10px; background-color: #d1ecf1; font-weight: bold;">RNF</td>
      <td style="padding: 10px;">Disponibilidade 99% (reduzir falhas).</td>
      <td style="padding: 10px; text-align: center; background-color: #d1ecf1;">Should</td>
      <td style="padding: 10px;">Processo Atual Q4 (implícito)</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><code>RN-001</code></td>
      <td style="padding: 10px; background-color: #ffeaa7; font-weight: bold;">RN</td>
      <td style="padding: 10px;">Notas sem vírgula (formato inteiro, conforme sistema legado).</td>
      <td style="padding: 10px; text-align: center; background-color: #fff3cd;">Must</td>
      <td style="padding: 10px;">Processo Atual Q1; Entrevista1.md</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><code>RN-002</code></td>
      <td style="padding: 10px; background-color: #ffeaa7; font-weight: bold;">RN</td>
      <td style="padding: 10px;">Lançamento por avaliação (frequência: bimestral/semestral).</td>
      <td style="padding: 10px; text-align: center; background-color: #d1ecf1;">Should</td>
      <td style="padding: 10px;">Processo Atual Q2</td>
    </tr>
    <tr>
      <td style="padding: 10px;"><code>RF-005</code></td>
      <td style="padding: 10px; background-color: #d4edda; font-weight: bold;">RF</td>
      <td style="padding: 10px;">Dashboard professor: visão notas/freqüência por turma.</td>
      <td style="padding: 10px; text-align: center; background-color: #f8f9fa;">Could</td>
      <td style="padding: 10px;">Necessidades Q2</td>
    </tr>
  </tbody>
</table>

<style>
.small-note { font-size: 0.9em; color: #666; margin-top: 10px; }
</style>
<div class="small-note">
<strong>Legenda:</strong> <span style="background-color: #d4edda;">RF (Funcional)</span> | 
<span style="background-color: #d1ecf1;">RNF (Não-Funcional)</span> | 
<span style="background-color: #ffeaa7;">RN (Regra de Negócio)</span> | 
<span style="background-color: #fff3cd;">Must/Should/Could</span>
</div>