# Gerenciamento de Políticas e Acessos no Azure

Este projeto contém anotações e práticas sobre **gerenciamento de políticas e controle de acessos no Microsoft Azure**, incluindo segurança, conformidade e proteção de recursos.

---

## Revisão do Portal de Confiança da Microsoft

No **Azure Trust Center**, é possível verificar que a Microsoft cumpre diversos regulamentos e certificações, como:

- **ISO/IEC**
- **SOC**
- **RGPD (GDPR)**

Esses padrões garantem a segurança e conformidade dos serviços da plataforma.

---

## Gerenciamento de Recursos

### Resource Groups e Locks

- **Resource Group**: Grupo lógico de recursos do Azure, utilizado para organizar e gerenciar serviços.
- **Locks**: Ferramenta utilizada para proteger recursos contra alterações acidentais.

**Tipos de Lock:**

- `Delete` → Impede a exclusão do recurso.
- `Read-only` → Impede alterações e exclusão do recurso.

**Exemplo prático:**

1. Foi criado um **Resource Group**.
2. Adicionado um **Lock de exclusão (`Delete`)** na VNet.
3. Tentativa de deletar a VNet falhou devido ao bloqueio, garantindo proteção do recurso.

---

## Azure Purview

- Navegação e gestão no **Purview Account**, que é a ferramenta de governança de dados do Azure.
- Permite catalogar, proteger e gerenciar dados corporativos de forma segura e conforme as políticas da empresa.

---

## Conclusão

O uso de **locks em recursos** e o **cumprimento de normas de conformidade** são essenciais para:

- Garantir a **segurança** dos recursos.
- Evitar **alterações ou exclusões acidentais**.
- Manter a **conformidade legal** dos dados e serviços utilizados.

---

**Status do Projeto:** 🚀 Em aprendizado  
**Tecnologia:** Microsoft Azure  
