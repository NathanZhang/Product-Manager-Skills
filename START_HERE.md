# Start Here

Pick one path and run it immediately.

## 1) I Need An Artifact

Use a component skill.

```bash
./scripts/run-pm.sh skill user-story "Write stories for a new account settings page"
```

Other strong starts:
- `positioning-statement`
- `problem-statement`
- `press-release`

## 2) I Need Help Deciding

Use an interactive skill.

```bash
./scripts/run-pm.sh skill prioritization-advisor "We have 12 requests and one sprint"
```

Other strong starts:
- `feature-investment-advisor`
- `finance-based-pricing-advisor`
- `business-health-diagnostic`

## 3) I Need End-To-End Guidance

Use a workflow skill or command.

```bash
./scripts/run-pm.sh command discover "Reduce onboarding drop-off for self-serve users"
```

Other command starts:
- `strategy`
- `write-prd`
- `plan-roadmap`

## Find The Right Capability Fast

```bash
./scripts/find-a-skill.sh --keyword onboarding
./scripts/find-a-command.sh --keyword roadmap
./scripts/find-a-command.sh --list-all
```

## Validate The Library

```bash
./scripts/test-library.sh
```
