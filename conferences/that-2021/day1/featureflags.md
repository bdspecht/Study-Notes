### Feature Flags - The Art of the IF and Deployment
* References
 * https://github.com/Codebytes/feature-flags
* What are feature flags
 * **It's an if**
 * Features flags can be simple configuration settings with Boolean values
* Why use feature flags?
 * Code separation
 * Minimize disruption to customers
 * Progressive roll-outs
 * A/B Testing
 * Kill switch
   * Example: Turn off feature if causing prod performance problems
* Short term
 * These are used to roll out new features or conduct experiments
 * They can be found anywhere, and can be more complex
 * They should be cleaned up after the roll-out or experiment
* Not all Flags are the same Long Term
 * Licensing
 * Advanced features
 * Integrations
 * Operational flags
 * Load management
* Deployment vs Release
 * Deployment
   * Low risk, repeatable, and routine
   * Installed on Production
   * Doesn't mean features are in use
 * Release
   * Higher risk
   * Business decision
   * Enables access to a feature
   * Allows experimentation
 * Limit the blast radius of change
  * Internal users -> Canary testing -> Progressive roll-outs -> full deployment
* Operationalizing flags
 * Features flag downsides
  * Features flags are technical debt
  * Harder to support and debug systems
  * Chaining flags is bad, ex: dependency problems
 * It's all about control
  * How do you to turn it on and off?
   * Per check-in?
   * Per server?
* Flag targeting
  * Targeting groups
   * Time
   * Region
   * User details
  * Triggers
   * Rise in failures
   * Load
* Flag best practices
 * Naming convention
 * Meaningful names with long descriptions
 * Central location for flags
 * Development team should share flags and configurations
 * Never re-purpose a feature flag
* SQL/JSON Models
 * Be additive, never change existing fields
 * If you have to remove a field, obsolete it until there is no possibility of a rollback
* Available products
  * Azure App Config
  * Launch Darkly
* Guidance
  * If running distributed, make sure you cache and store flags locally (context: Mobile)
