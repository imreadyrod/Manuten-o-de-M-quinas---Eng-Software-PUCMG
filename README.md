<h1><center>Agendamento de Manutenção em Múltiplas Máquinas<center></h1>
<section>
    <h2>1. Objetivo</h2>
    <p>O objetivo deste projeto é desenvolver um sistema de agendamento inteligente para a manutenção de equipamentos na indústria metalúrgica, garantindo a otimização dos recursos e a redução do tempo de inatividade das máquinas. O sistema priorizará automaticamente as manutenções com base em fatores como urgência, disponibilidade de mão de obra e recursos necessários para cada etapa do processo.</p>
</section>

<section>
    <h2>2. Problema</h2>
    <p>Atualmente, a programação da manutenção dos equipamentos na indústria é feita manualmente ou de forma ineficiente, resultando em atrasos, uso inadequado de recursos e aumento do tempo de inatividade dos equipamentos. A falta de um sistema automatizado de priorização e agendamento pode comprometer a produtividade da indústria e impactar a qualidade do processo industrial. O desafio é garantir que a sequência de manutenção de cada equipamento seja respeitada e que as ordens mais urgentes sejam atendidas primeiro, minimizando o impacto na produção.</p>
</section>

<section>
    <h2>3. Tipo de Solução</h2>
    <p>O sistema será uma aplicação web que irá permitir o agendamento dinâmico e automático das manutenções. A solução utilizará algoritmos de otimização para priorizar as ordens de manutenção e garantir que cada equipamento passe pelas etapas obrigatórias de manutenção de forma eficiente.</p>
</section>


<section>
    <h2>4. Requisitos Funcionais e Não Funcionais</h2>
    <p>Esta seção irá descrever os requisitos funcionais e não funcionais do sistema.</p>
    <section>
    <h3>4.1 Requisitos Funcionais</h3>
        <ul>
            <li>O sistema deve permitir o cadastro de equipamentos e suas respectivas sequências de manutenção.</li>
            <li>O sistema deve permitir o cadastro de ordens de manutenção e atribuir prioridades com base em critérios definidos.</li>
            <li>O sistema deve automatizar a distribuição das ordens entre as máquinas disponíveis considerando suas capacidades e restrições.</li>
            <li>O sistema deve permitir o monitoramento em tempo real do status de cada ordem de manutenção.</li>
            <li>O sistema deve permitir ajustes manuais nas ordens de manutenção, caso necessário.</li>
            <li>O sistema deve gerar relatórios de eficiência das manutenções realizadas.</li>
        </ul>
    </section>
    <section>
    <h3>4.2 Requisitos Não-Funcionais</h3>
        <ul>
            <li>A aplicação deve ser responsiva e acessível via dispositivos móveis e desktops.</li>
            <li>O sistema deve ter alta disponibilidade para evitar atrasos na produção.</li>
            <li>O sistema deve garantir a segurança dos dados, impedindo acessos não autorizados.</li>
            <li>O tempo de resposta para consulta e agendamento de manutenção deve ser inferior a 2 segundos.</li>
            <li>O sistema deve ser escalável para suportar um grande número de equipamentos e ordens de manutenção simultaneamente.</li>
        </ul>
    </section>
</section>

<section>
<h2>5. Diagrama de Caso de Uso</h2>
    <h3>5.1 Atores</h3>
        <ul>
            <li>Técnico de Manutenção: Registra a conclusão de cada etapa da manutenção.</li>
            <li>Gerente de Produção: Visualiza e ajusta o cronograma de manutenção.</li>
            <li>Sistema: Processa as prioridades e distribui as manutenções entre as máquinas.</li>
        </ul>
    <h3>5.2 Casos de Uso Principais</h3>
        <ul>
            <li>Cadastrar Equipamento: O gerente registra um novo equipamento no sistema, incluindo sua sequência de manutenção.</li>
            <li>Cadastrar Ordem de Manutenção: O gerente insere uma nova ordem e define sua prioridade.</li>
            <li>Gerar Cronograma de Manutenção: O sistema gera um cronograma otimizado automaticamente.</li>
            <li>Atualizar Status de Manutenção: O técnico marca uma etapa como concluída.</li>
            <li>Ajustar Cronograma Manualmente: O gerente pode modificar o agendamento caso necessário.</li>
            <li>Gerar Relatórios: O sistema produz relatórios de eficiência da manutenção.</li>
        </ul>
</section>
<img src="Imagens/Manutencao Equipamentos UML.jpg" alt="Diagrama de Caso de Uso" width="1000" height="500">














