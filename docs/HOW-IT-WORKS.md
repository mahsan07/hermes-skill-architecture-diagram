# How Architecture Diagram Works

Create dark, readable SVG architecture diagrams from system descriptions.

![Detailed systems blueprint for Architecture Diagram](../assets/system-blueprint.png)

## Stages

### 1. Extract named systems and boundaries

**Primary surface:** `System brief`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 2. Group components into readable layers

**Primary surface:** `Component inventory`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 3. Map protocols and trust boundaries

**Primary surface:** `Relationship model`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 4. Route connectors without visual collisions

**Primary surface:** `SVG layout engine`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 5. Render dark-theme SVG

**Primary surface:** `Validated diagram`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.
### 6. Inspect labels arrows and mobile scaling

**Primary surface:** `Validated diagram`

Record the input, operation, observable output, and any decision that changes scope. Stop here if the output is missing, contradictory, or insufficient for the next stage.

## Failure handling

- **Authorization failure:** do not probe credentials or broaden access; report the missing authority.
- **Target ambiguity:** stop before mutation and request the minimum identifying information.
- **Tool or service failure:** retain error evidence, retry only safe transient failures, and cap retries.
- **Verification failure:** classify the run as incomplete even when the preceding operation returned success.

## Completion evidence

The handoff should contain the original request, inspection state, preview or plan, exact execution result, direct verification, and a final receipt naming limitations and withheld actions.
