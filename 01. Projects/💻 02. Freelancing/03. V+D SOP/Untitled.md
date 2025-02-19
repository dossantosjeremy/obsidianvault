# Form to Template Variable Mapping

## Document Control & Basic Information
| Form Question | Template Variable | Notes |
|---------------|------------------|-------|
| Project Reference Number | {{project_reference}} | Direct mapping |
| *System Generated* | {{document_version}} | Auto-generated |
| *System Generated* | {{current_date}} | Auto-generated |
| Internal Review Required | {{document_status}} | Convert Yes/No to Draft/Final |

## Client Information
| Form Question | Template Variable | Notes |
|---------------|------------------|-------|
| Client Name | {{client_name}} | Used in multiple sections |
| Physical Address | {{client_address}} | Used in multiple sections |
| Contact Details (Email + Phone) | {{client_contact_details}} | Combine both fields |
| Organization Type + Service Requirements | {{service_type}} | Combine for executive summary |

## Project Overview
| Form Question | Template Variable | Notes |
|---------------|------------------|-------|
| Project Name | {{project_name}} | Direct mapping |
| Project Description | {{project_description}} | Direct mapping |
| Project Requirements | {{project_requirements}} | From requirements section |
| Project Objectives (Long Text) | {{objective_1}} {{objective_2}} {{objective_3}} | Parse text into separate objectives |

## Services & Scope
| Form Question | Template Variable | Notes |
|---------------|------------------|-------|
| Service Requirements (Core) | {{core_services_description}} | Generate from selections |
| Service Requirements + Architecture Details | {{service_package_1_name}} {{service_package_1_scope}} | Combine for first package |
| Service Requirements + Interior/Systems Details | {{service_package_2_name}} {{service_package_2_scope}} | Combine for second package |
| Project Specifics (Based on type) | {{deliverable_1}} {{deliverable_2}} {{deliverable_3}} | Generate from specifications |
| Additional Services | {{optional_services_description}} | From service selections |

## Timeline
| Form Question | Template Variable | Notes |
|---------------|------------------|-------|
| Start Date | {{start_date}} | Direct mapping |
| End Date | {{end_date}} | Direct mapping |
| Key Milestones | {{milestone_1_name}} {{milestone_1_date}} {{milestone_2_name}} {{milestone_2_date}} | Parse milestone text |
| Key Milestones (Combined) | {{delivery_schedule}} | Generate from milestone data |

## Financial Information
| Form Question | Template Variable | Notes |
|---------------|------------------|-------|
| Base Fee | {{total_fee}} | Direct mapping |
| Service Breakdown | {{service_1_name}} {{service_1_fee}} {{service_2_name}} {{service_2_fee}} {{service_3_name}} {{service_3_fee}} | Generate from fee structure |
| Payment Schedule | {{initial_payment}} {{initial_payment_percentage}} | Calculate from selection |
| Payment Schedule | {{milestone_1_payment_description}} {{milestone_1_payment}} {{milestone_2_payment_description}} {{milestone_2_payment}} {{milestone_3_payment_description}} {{milestone_3_payment}} | Generate from schedule |
| Additional Services Cost | {{additional_costs_description}} | Direct mapping |

## Legal & Terms
| Form Question | Template Variable | Notes |
|---------------|------------------|-------|
| *Standard Text* | {{ip_rights_terms}} | Pre-defined text |
| *Standard Text* | {{confidentiality_terms}} | Pre-defined text |
| *Standard Text* | {{change_management_terms}} | Pre-defined text |
| *Standard Text* | {{termination_terms}} | Pre-defined text |
| *Standard Text* | {{client_responsibilities}} | Pre-defined text |

## Team & Communication
| Form Question | Template Variable | Notes |
|---------------|------------------|-------|
| Project Director | {{project_director}} | Direct mapping |
| Design Director | {{design_director}} | Direct mapping |
| Creative Director | {{creative_director}} | Direct mapping |
| *System Generated* | {{communication_structure}} | Generate from team structure |

## Special Notes:

1. **Automated Fields**:
   - Document version
   - Current date
   - Standard legal text
   - Communication structure

2. **Compound Fields**:
   - Service descriptions (combine multiple selections)
   - Deliverables (generate from project specifics)
   - Payment schedules (calculate from selections)

3. **Parsing Required**:
   - Project objectives (from long text to separate points)
   - Milestones (from long text to structured timeline)
   - Service packages (from multiple selections to structured packages)