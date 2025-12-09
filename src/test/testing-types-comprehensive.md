<!-- COMPREHENSIVE TESTING TYPES SECTION - For mt-intro-fund.html -->
<!-- This replaces the existing Testing Types tab content -->

<div id="tab5" class="tab-content">
    <div class="tab-header">
        <h2>🎯 Complete Testing Types Classification & Framework</h2>
        <p class="subtitle">Master 27+ testing types with real-world examples, visual diagrams, and decision matrices</p>
    </div>

    <!-- Quick Statistics -->
    <div class="stats-container">
        <div class="stat-box">
            <div class="stat-number">27+</div>
            <div class="stat-label">Testing Types</div>
        </div>
        <div class="stat-box">
            <div class="stat-number">$1→$1000+</div>
            <div class="stat-label">Cost Multiplier</div>
        </div>
        <div class="stat-box">
            <div class="stat-number">80%</div>
            <div class="stat-label">Execution Time</div>
        </div>
        <div class="stat-box">
            <div class="stat-number">10x</div>
            <div class="stat-label">Dev vs Production</div>
        </div>
    </div>

    <!-- Testing Classification Overview -->
    <section class="testing-overview">
        <h3>🔍 Testing Classification Framework</h3>
        <p>Software testing is divided into two fundamental categories that work synergistically:</p>
        
        <div class="classification-grid">
            <div class="classification-card functional">
                <div class="card-icon">✓</div>
                <h4>Functional Testing</h4>
                <p class="card-subtitle">Tests WHAT the software does</p>
                <ul class="features-list">
                    <li>✓ Requirement validation</li>
                    <li>✓ Business logic verification</li>
                    <li>✓ Feature functionality</li>
                    <li>✓ User workflows</li>
                </ul>
                <div class="card-stat">13+ Types</div>
            </div>
            
            <div class="classification-card non-functional">
                <div class="card-icon">⚙️</div>
                <h4>Non-Functional Testing</h4>
                <p class="card-subtitle">Tests HOW the software works</p>
                <ul class="features-list">
                    <li>✓ Performance metrics</li>
                    <li>✓ Quality attributes</li>
                    <li>✓ System reliability</li>
                    <li>✓ User experience</li>
                </ul>
                <div class="card-stat">14+ Types</div>
            </div>
        </div>
    </section>

    <!-- FUNCTIONAL TESTING TYPES -->
    <section class="testing-types-section">
        <h3>📋 Functional Testing Types (13+ Complete)</h3>
        
        <!-- 1. UNIT TESTING -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>1️⃣ Unit Testing</h4>
                <span class="badge developer">Developers</span>
                <span class="badge whitebox">White Box</span>
            </div>
            <div class="card-content">
                <div class="content-grid">
                    <div class="content-item">
                        <strong>🎯 What:</strong> Individual module/function testing
                    </div>
                    <div class="content-item">
                        <strong>⏰ When:</strong> During development
                    </div>
                    <div class="content-item">
                        <strong>👤 Who:</strong> Developers only
                    </div>
                    <div class="content-item">
                        <strong>📊 Coverage:</strong> Code level
                    </div>
                </div>
                
                <div class="example-box">
                    <strong>💡 Real-World Example:</strong>
                    <div class="example-content">
                        Testing login() function with:
                        <ul>
                            <li>Valid credentials → Login succeeds</li>
                            <li>Invalid password → Error message</li>
                            <li>Empty fields → Validation error</li>
                            <li>Special characters → Secure handling</li>
                            <li>SQL injection → Blocked</li>
                        </ul>
                    </div>
                </div>

                <div class="flow-diagram">
                    <div class="flow-step">Code Written</div>
                    <div class="arrow">→</div>
                    <div class="flow-step">Unit Tests Created</div>
                    <div class="arrow">→</div>
                    <div class="flow-step">Pass/Fix</div>
                    <div class="arrow">→</div>
                    <div class="flow-step">Next Module</div>
                </div>

                <div class="key-points">
                    <strong>📌 Key Points:</strong>
                    <ul>
                        <li>Fastest feedback loop for developers</li>
                        <li>Catches bugs early (10x cheaper to fix)</li>
                        <li>Uses frameworks: JUnit, TestNG, NUnit</li>
                        <li>Automated and repeatable</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 2. INTEGRATION TESTING -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>2️⃣ Integration Testing</h4>
                <span class="badge both">Devs + QA</span>
                <span class="badge graybox">Gray Box</span>
            </div>
            <div class="card-content">
                <div class="content-grid">
                    <div class="content-item">
                        <strong>🎯 What:</strong> Module interaction testing
                    </div>
                    <div class="content-item">
                        <strong>⏰ When:</strong> After unit testing
                    </div>
                    <div class="content-item">
                        <strong>👤 Who:</strong> Developers + QA
                    </div>
                    <div class="content-item">
                        <strong>📊 Focus:</strong> Module interfaces
                    </div>
                </div>

                <div class="approaches-box">
                    <strong>🔄 Three Integration Approaches:</strong>
                    <div class="approach-item approach-1">
                        <span class="approach-name">↓ Top-Down</span>
                        <span>Test high-level first, use stubs for lower modules</span>
                    </div>
                    <div class="approach-item approach-2">
                        <span class="approach-name">↑ Bottom-Up</span>
                        <span>Test low-level first, use drivers for upper modules</span>
                    </div>
                    <div class="approach-item approach-3">
                        <span class="approach-name">💥 Big Bang</span>
                        <span>Combine all at once (risky, not recommended)</span>
                    </div>
                </div>

                <div class="example-box">
                    <strong>💡 Real Example - Money Transfer:</strong>
                    <div class="example-content">
                        <table class="mini-table">
                            <tr>
                                <td><strong>Module 1:</strong> Debit Service</td>
                                <td><strong>Module 2:</strong> Credit Service</td>
                            </tr>
                            <tr>
                                <td>✓ Debit Account A: $100</td>
                                <td>✓ Credit Account B: $100</td>
                            </tr>
                            <tr>
                                <td colspan="2"><strong>Integration Test:</strong> Verify money flows correctly from A to B without loss or duplication</td>
                            </tr>
                        </table>
                    </div>
                </div>
            </div>
        </div>

        <!-- 3. SYSTEM TESTING -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>3️⃣ System Testing</h4>
                <span class="badge qa">QA Team</span>
                <span class="badge blackbox">Black Box</span>
            </div>
            <div class="card-content">
                <div class="content-grid">
                    <div class="content-item">
                        <strong>🎯 What:</strong> Complete end-to-end system
                    </div>
                    <div class="content-item">
                        <strong>⏰ When:</strong> After integration passes
                    </div>
                    <div class="content-item">
                        <strong>👤 Who:</strong> QA Team only
                    </div>
                    <div class="content-item">
                        <strong>🌍 Environment:</strong> Production-like
                    </div>
                </div>

                <div class="example-box">
                    <strong>💡 Real Example - Banking Loan Application:</strong>
                    <div class="workflow-chain">
                        <div class="workflow-item">Submission</div>
                        <div class="workflow-arrow">→</div>
                        <div class="workflow-item">Verification</div>
                        <div class="workflow-arrow">→</div>
                        <div class="workflow-item">Approval</div>
                        <div class="workflow-arrow">→</div>
                        <div class="workflow-item">Disbursement</div>
                        <div class="workflow-arrow">→</div>
                        <div class="workflow-item">Confirmation</div>
                    </div>
                    <p>Testing includes: Document validation, Interest calculation, EMI generation, Risk assessment</p>
                </div>

                <div class="key-points">
                    <strong>📌 Testing Scope:</strong>
                    <ul>
                        <li>Business workflows as per requirements</li>
                        <li>Database integrity and data flow</li>
                        <li>Integration with all dependent systems</li>
                        <li>Performance under expected load</li>
                        <li>Security and error handling</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 4. UAT -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>4️⃣ User Acceptance Testing (UAT)</h4>
                <span class="badge business">Business Users</span>
                <span class="badge blackbox">Black Box</span>
            </div>
            <div class="card-content">
                <div class="content-grid">
                    <div class="content-item">
                        <strong>🎯 What:</strong> End-user final validation
                    </div>
                    <div class="content-item">
                        <strong>⏰ When:</strong> Before go-live
                    </div>
                    <div class="content-item">
                        <strong>👤 Who:</strong> Business experts, customers
                    </div>
                    <div class="content-item">
                        <strong>📊 Data:</strong> Real business scenarios
                    </div>
                </div>

                <div class="uat-variants">
                    <div class="variant-item">
                        <strong>🏢 Alpha Testing:</strong> At developer's office with domain experts
                    </div>
                    <div class="variant-item">
                        <strong>🌐 Beta Testing:</strong> At customer site before production release
                    </div>
                </div>

                <div class="example-box">
                    <strong>💡 Real Example - E-Commerce Platform:</strong>
                    <p>FedEx employees test the shipping system with:</p>
                    <ul>
                        <li>Real shipping addresses and routes</li>
                        <li>Current carrier pricing</li>
                        <li>Actual tracking integration</li>
                        <li>Real payment processing</li>
                        <li>Actual business workflows</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 5. SMOKE TESTING -->
        <div class="testing-type-card highlight-critical">
            <div class="card-header" style="background: linear-gradient(135deg, #FF9800 0%, #f57c00 100%);">
                <h4>🔥 5️⃣ Smoke Testing (Build Verification)</h4>
                <span class="badge urgent">CRITICAL</span>
                <span class="badge quick">Fast</span>
            </div>
            <div class="card-content">
                <div class="content-grid">
                    <div class="content-item">
                        <strong>🎯 What:</strong> Quick sanity check
                    </div>
                    <div class="content-item">
                        <strong>⏰ When:</strong> IMMEDIATELY on new build
                    </div>
                    <div class="content-item">
                        <strong>⏱️ Duration:</strong> 30 min - 2 hours
                    </div>
                    <div class="content-item">
                        <strong>🧪 Type:</strong> Positive only (valid data)
                    </div>
                </div>

                <div class="critical-checks">
                    <strong>✅ Critical Checks:</strong>
                    <div class="check-item">
                        <span class="check-icon">✓</span> Application launches
                    </div>
                    <div class="check-item">
                        <span class="check-icon">✓</span> Login functionality works
                    </div>
                    <div class="check-item">
                        <span class="check-icon">✓</span> Homepage loads correctly
                    </div>
                    <div class="check-item">
                        <span class="check-icon">✓</span> Navigation accessible
                    </div>
                    <div class="check-item">
                        <span class="check-icon">✓</span> Critical features responsive
                    </div>
                    <div class="check-item">
                        <span class="check-icon">✓</span> No immediate crashes
                    </div>
                </div>

                <div class="alert-box warning">
                    <strong>⚠️ CRITICAL DECISION:</strong>
                    <p>If ANY check FAILS → <span class="highlight-red">REJECT BUILD IMMEDIATELY</span></p>
                    <p>Don't waste time on detailed testing of broken builds!</p>
                </div>

                <div class="benefit-box">
                    <strong>💰 Business Value:</strong> Smoke testing can catch blockers in 30 minutes that would waste weeks of testing time on broken builds
                </div>
            </div>
        </div>

        <!-- 6. SANITY TESTING -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>6️⃣ Sanity Testing</h4>
                <span class="badge qa">QA Focus</span>
                <span class="badge deep">Deep Testing</span>
            </div>
            <div class="card-content">
                <div class="comparison-table">
                    <table class="compare-table">
                        <tr>
                            <td><strong>vs Smoke Testing</strong></td>
                            <td>Narrow & Deep (vs Wide & Shallow)</td>
                        </tr>
                        <tr>
                            <td><strong>Focus</strong></td>
                            <td>Critical features ONLY</td>
                        </tr>
                        <tr>
                            <td><strong>Approach</strong></td>
                            <td>Manual, experience-based, unscripted</td>
                        </tr>
                        <tr>
                            <td><strong>Testers</strong></td>
                            <td>Experienced QA engineers</td>
                        </tr>
                    </table>
                </div>

                <div class="example-box">
                    <strong>💡 Example - Banking App:</strong>
                    <p>Thoroughly test each critical feature:</p>
                    <ul>
                        <li>Login: 5+ scenarios (valid, invalid, timeout, password reset)</li>
                        <li>Money Transfer: 8+ scenarios (same bank, different bank, failed)</li>
                        <li>Balance Check: 4+ scenarios (balance display, currency formats)</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 7. REGRESSION TESTING -->
        <div class="testing-type-card highlight-star">
            <div class="card-header" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);">
                <h4>⭐ 7️⃣ Regression Testing</h4>
                <span class="badge critical">CRITICAL</span>
                <span class="badge repeated">Repetitive</span>
            </div>
            <div class="card-content">
                <div class="alert-box danger">
                    <strong>⚡ Why Critical:</strong>
                    <p>One bug fix can break 5 other features you didn't expect!</p>
                </div>

                <div class="regression-types-box">
                    <strong>🔄 Three Regression Types:</strong>
                    
                    <div class="reg-type-item">
                        <div class="reg-type-header">Unit Regression</div>
                        <div class="reg-type-content">
                            <strong>Scope:</strong> Only changed code
                            <p>Fastest but incomplete</p>
                        </div>
                    </div>

                    <div class="reg-type-item">
                        <div class="reg-type-header">Regional Regression ⭐ RECOMMENDED</div>
                        <div class="reg-type-content">
                            <strong>Scope:</strong> Changed code + impact areas
                            <p>Balanced approach for production quality</p>
                        </div>
                    </div>

                    <div class="reg-type-item">
                        <div class="reg-type-header">Full Regression</div>
                        <div class="reg-type-content">
                            <strong>Scope:</strong> Entire application
                            <p>Time-consuming but thorough (use for critical releases)</p>
                        </div>
                    </div>
                </div>

                <div class="solution-box">
                    <strong>💡 Solution:</strong> Automate regression testing with Selenium/Cypress for efficient re-execution
                </div>

                <div class="flow-diagram">
                    <div class="flow-step">Developer Fixes Bug</div>
                    <div class="arrow">→</div>
                    <div class="flow-step">Run Regression Suite</div>
                    <div class="arrow">→</div>
                    <div class="flow-step">Verify No New Failures</div>
                    <div class="arrow">→</div>
                    <div class="flow-step">PASS/FAIL Decision</div>
                </div>

                <div class="key-points">
                    <strong>📌 Key Points:</strong>
                    <ul>
                        <li>Execute after EVERY code change</li>
                        <li>Maintain regression test suite continuously</li>
                        <li>Automate for faster feedback</li>
                        <li>Balance coverage vs execution time</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 8. RETESTING -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>8️⃣ Retesting vs Regression</h4>
                <span class="badge compare">Comparison</span>
            </div>
            <div class="card-content">
                <table class="comparison-table-full">
                    <thead>
                        <tr>
                            <th>Aspect</th>
                            <th>Retesting</th>
                            <th>Regression Testing</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td><strong>Definition</strong></td>
                            <td>Testing a specific bug fix</td>
                            <td>Ensuring fix doesn't break others</td>
                        </tr>
                        <tr>
                            <td><strong>Scope</strong></td>
                            <td>ONLY the specific bug</td>
                            <td>ENTIRE application/modules</td>
                        </tr>
                        <tr>
                            <td><strong>Test Cases</strong></td>
                            <td>1-3 test cases</td>
                            <td>100+ test cases</td>
                        </tr>
                        <tr>
                            <td><strong>When</strong></td>
                            <td>After each individual fix</td>
                            <td>After all fixes in cycle</td>
                        </tr>
                        <tr>
                            <td><strong>Timeline</strong></td>
                            <td>Few minutes</td>
                            <td>Hours to days</td>
                        </tr>
                        <tr>
                            <td><strong>Sequential</strong></td>
                            <td>Bug Found → Fixed → Retest ✓</td>
                            <td>Fixes Collected → Regression ✓</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>

        <!-- 9. END-TO-END TESTING -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>9️⃣ End-to-End (E2E) Testing</h4>
                <span class="badge workflow">Full Workflow</span>
                <span class="badge integration">Complete</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Complete business workflow from start to finish including all systems and data</p>

                <div class="example-box">
                    <strong>💡 E-Commerce Complete Workflow:</strong>
                    <div class="workflow-chain">
                        <div class="workflow-item">👤 Login</div>
                        <div class="workflow-arrow">→</div>
                        <div class="workflow-item">🛍️ Browse</div>
                        <div class="workflow-arrow">→</div>
                        <div class="workflow-item">🛒 Add to Cart</div>
                        <div class="workflow-arrow">→</div>
                        <div class="workflow-item">💳 Checkout</div>
                        <div class="workflow-arrow">→</div>
                        <div class="workflow-item">💰 Payment</div>
                        <div class="workflow-arrow">→</div>
                        <div class="workflow-item">✉️ Confirmation</div>
                        <div class="workflow-arrow">→</div>
                        <div class="workflow-item">📦 Tracking</div>
                    </div>
                </div>

                <div class="key-points">
                    <strong>📌 Key Characteristics:</strong>
                    <ul>
                        <li>Uses REAL production-like data throughout</li>
                        <li>Tests multiple systems integration</li>
                        <li>Validates complete business processes</li>
                        <li>Often automated for continuous testing</li>
                        <li>Takes hours/days to complete fully</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 10. AD-HOC TESTING -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>🔟 Ad-Hoc Testing (Monkey Testing)</h4>
                <span class="badge random">Random</span>
                <span class="badge experience">Experience-Based</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Random, unplanned testing without predefined test cases or procedures</p>

                <div class="alert-box info">
                    <strong>💡 Why Important:</strong>
                    <p>Real end-users behave unpredictably and randomly, not systematically like trained QA engineers!</p>
                </div>

                <div class="adhoc-examples">
                    <strong>🔴 Real Ad-Hoc Test Scenarios:</strong>
                    <div class="adhoc-item">
                        <span class="scenario-icon">1</span>
                        <span class="scenario-text">Login → Immediately click Back (should NOT show inbox/dashboard)</span>
                    </div>
                    <div class="adhoc-item">
                        <span class="scenario-icon">2</span>
                        <span class="scenario-text">Copy URL → Logout → Paste old URL in browser (should NOT access)</span>
                    </div>
                    <div class="adhoc-item">
                        <span class="scenario-icon">3</span>
                        <span class="scenario-text">Rapid clicks on submit button multiple times (should handle gracefully)</span>
                    </div>
                    <div class="adhoc-item">
                        <span class="scenario-icon">4</span>
                        <span class="scenario-text">Browser back/forward while form is being filled (should preserve data)</span>
                    </div>
                    <div class="adhoc-item">
                        <span class="scenario-icon">5</span>
                        <span class="scenario-text">Open 10 browser tabs with app (should handle multiple sessions)</span>
                    </div>
                </div>

                <div class="benefit-box">
                    <strong>🎯 Real Benefit:</strong>
                    <p>Ad-hoc testing often finds bugs that systematic, scripted testing completely misses because it mimics ACTUAL USER BEHAVIOR!</p>
                </div>
            </div>
        </div>

        <!-- 11. EXPLORATORY TESTING -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>1️⃣1️⃣ Exploratory Testing</h4>
                <span class="badge unscripted">Unscripted</span>
                <span class="badge learning">Learning</span>
            </div>
            <div class="card-content">
                <div class="content-grid">
                    <div class="content-item">
                        <strong>🎯 What:</strong> Simultaneous design and execution without pre-plans
                    </div>
                    <div class="content-item">
                        <strong>👤 Who:</strong> Experienced testers with domain knowledge
                    </div>
                    <div class="content-item">
                        <strong>⏰ When:</strong> Requirements unclear OR exploring behavior
                    </div>
                    <div class="content-item">
                        <strong>🔄 Process:</strong> Learn → Test → Adapt → Continue
                    </div>
                </div>

                <div class="flow-diagram">
                    <div class="flow-step">Understand Requirements</div>
                    <div class="arrow">→</div>
                    <div class="flow-step">Create Initial Test</div>
                    <div class="arrow">→</div>
                    <div class="flow-step">Observe Behavior</div>
                    <div class="arrow">→</div>
                    <div class="flow-step">Adapt Next Test</div>
                    <div class="arrow">→</div>
                    <div class="flow-step">Find Hidden Bugs</div>
                </div>

                <div class="key-points">
                    <strong>📝 Important Note:</strong>
                    <p>Even though exploratory testing is unscripted, ALWAYS document your findings for future reference and knowledge transfer!</p>
                </div>
            </div>
        </div>

        <!-- 12. MUTATION TESTING -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>1️⃣2️⃣ Mutation Testing</h4>
                <span class="badge quality">Quality Check</span>
                <span class="badge developer">Developers</span>
            </div>
            <div class="card-content">
                <p><strong>Purpose:</strong> Verify tester quality and test case effectiveness</p>

                <div class="flow-diagram">
                    <div class="flow-step" style="background: #ff9800;">
                        <strong>Step 1</strong><br>Inject Defects
                    </div>
                    <div class="arrow">→</div>
                    <div class="flow-step" style="background: #2196f3;">
                        <strong>Step 2</strong><br>Testers Test
                    </div>
                    <div class="arrow">→</div>
                    <div class="flow-step" style="background: #4caf50;">
                        <strong>Step 3</strong><br>Defects Caught?
                    </div>
                </div>

                <div class="key-points">
                    <strong>📌 Interpretation:</strong>
                    <ul>
                        <li>✅ If injected defects are CAUGHT → Test quality is GOOD</li>
                        <li>❌ If injected defects are MISSED → Test quality is POOR</li>
                        <li>🔄 Developers intentionally introduce bugs</li>
                        <li>📊 Helps measure test case effectiveness</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 13. EXHAUSTIVE TESTING -->
        <div class="testing-type-card">
            <div class="card-header">
                <h4>1️⃣3️⃣ Exhaustive Testing</h4>
                <span class="badge comprehensive">Comprehensive</span>
                <span class="badge intensive">Time-Intensive</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Testing ALL possible positive AND negative scenarios for a feature</p>

                <div class="alert-box danger">
                    <strong>🔴 Reality Check:</strong>
                    <p>Often MATHEMATICALLY IMPOSSIBLE due to combinatorial explosion!</p>
                </div>

                <div class="example-box">
                    <strong>💡 Example - Registration Form:</strong>
                    <div class="calculation">
                        <p><strong>Given:</strong></p>
                        <ul>
                            <li>15 input fields (Name, Email, Password, Age, etc.)</li>
                            <li>5 possible values per field (valid, invalid, empty, special chars, boundary)</li>
                        </ul>
                        <p><strong>Total Test Combinations:</strong> 5^15 = <span style="color: red; font-weight: bold;">30 BILLION test cases!</span></p>
                        <p style="margin-top: 1rem;">At 1 second per test = <span style="color: red; font-weight: bold;">952 years of testing!</span></p>
                    </div>
                </div>

                <div class="usage-box">
                    <strong>🎯 When Used:</strong>
                    <p>Only for CRITICAL features where:</p>
                    <ul>
                        <li>Safety is paramount (airline software, medical devices)</li>
                        <li>Security is critical (banking, payment systems)</li>
                        <li>Cost of failure is astronomical</li>
                        <li>Subset of exhaustive testing is practical</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- NON-FUNCTIONAL TESTING TYPES -->
    <section class="testing-types-section">
        <h3>⚙️ Non-Functional Testing Types (14+ Complete)</h3>
        
        <!-- 1. PERFORMANCE TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #FF6B6B 0%, #EE5A52 100%);">
                <h4>⚡ Performance Testing</h4>
                <span class="badge speed">Speed</span>
                <span class="badge efficiency">Efficiency</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Response time, throughput, resource usage under NORMAL conditions</p>

                <div class="metrics-box">
                    <strong>📊 Key Metrics Measured:</strong>
                    <div class="metric-item">
                        <span class="metric-name">Response Time:</span>
                        <span class="metric-value">⏱️ How fast page loads (target < 2 sec)</span>
                    </div>
                    <div class="metric-item">
                        <span class="metric-name">Throughput:</span>
                        <span class="metric-value">📈 Requests/sec the system handles</span>
                    </div>
                    <div class="metric-item">
                        <span class="metric-name">CPU Usage:</span>
                        <span class="metric-value">🔧 Processor utilization percentage</span>
                    </div>
                    <div class="metric-item">
                        <span class="metric-name">Memory Usage:</span>
                        <span class="metric-value">🧠 RAM consumption during execution</span>
                    </div>
                    <div class="metric-item">
                        <span class="metric-name">Disk I/O:</span>
                        <span class="metric-value">💾 Data read/write speed</span>
                    </div>
                </div>

                <div class="tools-box">
                    <strong>🛠️ Tools:</strong> JMeter, LoadRunner, Gatling, New Relic
                </div>
            </div>
        </div>

        <!-- 2. LOAD TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #4ECDC4 0%, #44A08D 100%);">
                <h4>📊 Load Testing</h4>
                <span class="badge heavy">Heavy Users</span>
                <span class="badge capacity">Capacity</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Application behavior under heavy concurrent user LOAD</p>

                <div class="example-box">
                    <strong>💡 Real Examples:</strong>
                    <ul>
                        <li>Black Friday: 10,000 users shopping simultaneously</li>
                        <li>Banking Portal: 5,000 concurrent users during lunch break</li>
                        <li>Social Media: 100,000+ concurrent users during live event</li>
                        <li>Ticketing: 50,000 users buying tickets at midnight</li>
                    </ul>
                </div>

                <div class="goal-box">
                    <strong>🎯 Goal:</strong>
                    <p>Find MAXIMUM number of concurrent users the system can handle before degradation begins</p>
                </div>

                <div class="performance-chart">
                    <strong>📈 Typical Load Test Graph:</strong>
                    <div style="background: #f5f5f5; padding: 1rem; border-radius: 5px; margin: 1rem 0;">
                        <pre style="text-align: center; font-size: 0.9em;">
Response Time
    ↑      ╱╱╱╱ (Performance degrades)
    │    ╱╱    ╲╲╲╲ (System breaks)
    │  ╱╱        ╲╲╲╲╲
    │╱────────────────→ Concurrent Users
        ↑          ↑          ↑
     Optimal   Max Users   Breaking Point
                        </pre>
                    </div>
                </div>
            </div>
        </div>

        <!-- 3. STRESS TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #FF6B9D 0%, #C44569 100%);">
                <h4>💥 Stress Testing</h4>
                <span class="badge breaking">Breaking Point</span>
                <span class="badge extreme">Extreme Load</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Application tested BEYOND maximum capacity to find breaking point</p>

                <div class="stress-scenarios">
                    <strong>🔴 Stress Test Scenarios:</strong>
                    <div class="scenario-item">
                        💥 Double the expected load
                    </div>
                    <div class="scenario-item">
                        🔌 Hardware failures (server down)
                    </div>
                    <div class="scenario-item">
                        🌐 Network issues (high latency)
                    </div>
                    <div class="scenario-item">
                        🔐 Database locked/slow
                    </div>
                    <div class="scenario-item">
                        ⏱️ Timeout scenarios
                    </div>
                </div>

                <div class="expectation-box">
                    <strong>✅ Expected Behavior:</strong>
                    <p>System should handle failure gracefully:</p>
                    <ul>
                        <li>❌ Does NOT crash or corrupt data</li>
                        <li>✓ Shows appropriate error messages</li>
                        <li>✓ Recovers when load decreases</li>
                        <li>✓ Logs errors for debugging</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 4. USABILITY TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);">
                <h4>😊 Usability Testing</h4>
                <span class="badge ux">User Experience</span>
                <span class="badge ui">UI/UX</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> How easily end-users can understand and use the application</p>

                <div class="usability-questions">
                    <strong>❓ Questions Evaluated:</strong>
                    <ul>
                        <li>Can users complete basic tasks easily?</li>
                        <li>Is the interface intuitive and clear?</li>
                        <li>Are buttons positioned logically?</li>
                        <li>Are colors and fonts professional?</li>
                        <li>Can new users navigate without help?</li>
                        <li>Are error messages understandable?</li>
                        <li>Is the workflow natural?</li>
                    </ul>
                </div>

                <div class="key-points">
                    <strong>👤 Best Feedback From:</strong>
                    <p>Non-technical end-users and actual customers (not programmers or QA testers!)</p>
                </div>
            </div>
        </div>

        <!-- 5. COMPATIBILITY TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #00BCD4 0%, #0097A7 100%);">
                <h4>🖥️ Compatibility Testing</h4>
                <span class="badge cross">Cross-Platform</span>
                <span class="badge environments">Environments</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Application works correctly on various hardware, OS, and browser combinations</p>

                <div class="compat-matrix">
                    <strong>🔍 Compatibility Matrix:</strong>
                    
                    <div class="compat-category">
                        <strong>🖥️ Operating Systems:</strong>
                        <span>Windows 10/11, macOS, Linux, iOS, Android</span>
                    </div>

                    <div class="compat-category">
                        <strong>🌐 Browsers:</strong>
                        <span>Chrome, Firefox, Safari, Edge, IE11</span>
                    </div>

                    <div class="compat-category">
                        <strong>📱 Devices:</strong>
                        <span>Desktop, Laptop, Tablet, Smartphone, Smart TV</span>
                    </div>

                    <div class="compat-category">
                        <strong>📐 Screen Resolutions:</strong>
                        <span>1024×768, 1366×768, 1920×1080, 2560×1440, Mobile resolutions</span>
                    </div>

                    <div class="compat-category">
                        <strong>🔋 Network Conditions:</strong>
                        <span>4G, 5G, WiFi, Slow networks, Offline mode</span>
                    </div>
                </div>

                <div class="strategy-box">
                    <strong>💡 Strategy:</strong>
                    <p>Don't test ALL combinations (1000s possible)! Focus on:</p>
                    <ul>
                        <li>Most widely used platforms (market share data)</li>
                        <li>Customer requirements</li>
                        <li>Business priorities</li>
                        <li>ROI on testing effort</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 6. SECURITY TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #E53935 0%, #C62828 100%);">
                <h4>🔐 Security Testing</h4>
                <span class="badge protection">Data Protection</span>
                <span class="badge critical">Critical</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Verifying all security conditions are properly implemented</p>

                <div class="security-tests">
                    <strong>🔍 Security Test Categories:</strong>
                    
                    <div class="sec-test-item">
                        <span class="sec-test-name">SQL Injection:</span>
                        <span class="sec-test-desc">Testing for database attacks</span>
                    </div>

                    <div class="sec-test-item">
                        <span class="sec-test-name">XSS (Cross-Site Scripting):</span>
                        <span class="sec-test-desc">Testing for script injection attacks</span>
                    </div>

                    <div class="sec-test-item">
                        <span class="sec-test-name">Authentication Bypass:</span>
                        <span class="sec-test-desc">Testing login security</span>
                    </div>

                    <div class="sec-test-item">
                        <span class="sec-test-name">Authorization Bypass:</span>
                        <span class="sec-test-desc">Testing permission controls</span>
                    </div>

                    <div class="sec-test-item">
                        <span class="sec-test-name">Data Encryption:</span>
                        <span class="sec-test-desc">Testing data is encrypted in transit & at rest</span>
                    </div>

                    <div class="sec-test-item">
                        <span class="sec-test-name">Session Management:</span>
                        <span class="sec-test-desc">Testing session timeouts and hijacking</span>
                    </div>
                </div>

                <div class="tools-box">
                    <strong>🛠️ Security Testing Tools:</strong>
                    <p>Burp Suite, OWASP ZAP, Nessus, Metasploit</p>
                </div>

                <div class="alert-box danger">
                    <strong>⚠️ High Stakes:</strong>
                    <p>Security flaws can lead to:</p>
                    <ul>
                        <li>💰 Data theft and financial loss</li>
                        <li>🔒 Loss of customer trust</li>
                        <li>⚖️ Legal action and penalties</li>
                        <li>📉 Brand damage</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 7. RELIABILITY TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #7E57C2 0%, #5E35B1 100%);">
                <h4>📈 Reliability Testing</h4>
                <span class="badge continuous">Continuous</span>
                <span class="badge stability">Stability</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Application functions correctly continuously for extended periods</p>

                <div class="reliability-metrics">
                    <strong>📊 Reliability Metrics:</strong>
                    <div class="metric-item">
                        <span class="metric-name">MTBF (Mean Time Between Failures):</span>
                        <span class="metric-value">How long until next crash</span>
                    </div>
                    <div class="metric-item">
                        <span class="metric-name">MTTR (Mean Time To Recovery):</span>
                        <span class="metric-value">How long to restart normally</span>
                    </div>
                    <div class="metric-item">
                        <span class="metric-name">Availability:</span>
                        <span class="metric-value">99.9% uptime target</span>
                    </div>
                </div>

                <div class="example-box">
                    <strong>💡 Real-World Scenario:</strong>
                    <p>Your mobile phone after 10 days of continuous use may:</p>
                    <ul>
                        <li>Slow down due to RAM buildup</li>
                        <li>Freeze intermittently</li>
                        <li>Battery drain faster</li>
                        <li>Apps crash unexpectedly</li>
                    </ul>
                    <p>Reliability testing catches these long-term issues.</p>
                </div>

                <div class="key-points">
                    <strong>📌 Reliability Testing Process:</strong>
                    <ul>
                        <li>Run automated scripts for 48-72 hours continuously</li>
                        <li>Monitor system behavior and resource usage</li>
                        <li>Log every failure and error</li>
                        <li>Calculate MTBF statistics</li>
                        <li>Identify memory leaks and resource exhaustion</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 8. RECOVERY TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #F57C00 0%, #E65100 100%);">
                <h4>🔄 Recovery Testing</h4>
                <span class="badge disaster">Disaster Recovery</span>
                <span class="badge resilience">Resilience</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> How well the system recovers from failures and unexpected situations</p>

                <div class="recovery-scenarios">
                    <strong>🔴 Failure Scenarios to Test:</strong>
                    <div class="scenario-item">
                        💥 Sudden power failure (unplug server)
                    </div>
                    <div class="scenario-item">
                        🌐 Network disconnection (unplug ethernet)
                    </div>
                    <div class="scenario-item">
                        🔴 Database crash or lockup
                    </div>
                    <div class="scenario-item">
                        💾 Disk full error
                    </div>
                    <div class="scenario-item">
                        🔐 Authentication server down
                    </div>
                    <div class="scenario-item">
                        ⏱️ Timeout scenarios
                    </div>
                </div>

                <div class="recovery-expected">
                    <strong>✅ Expected Recovery:</strong>
                    <ul>
                        <li>❌ Application does NOT corrupt data</li>
                        <li>✓ Automatic restart on power restoration</li>
                        <li>✓ Restore to previous stable state</li>
                        <li>✓ Log all errors and recovery actions</li>
                        <li>✓ Notify users appropriately</li>
                    </ul>
                </div>

                <div class="example-box">
                    <strong>💡 Real Example - Firefox Recovery:</strong>
                    <p>After power failure, Firefox shows:</p>
                    <div style="background: #f5f5f5; padding: 1rem; border-radius: 5px; margin: 0.5rem 0;">
                        <p style="color: #0066cc;">✓ "Restore Previous Session?"</p>
                        <p>Click Yes → All tabs and data restored</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- 9. AUTHORIZATION & AUTHENTICATION -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #1976D2 0%, #1565C0 100%);">
                <h4>🔑 Authorization & Authentication</h4>
                <span class="badge access">Access Control</span>
                <span class="badge identity">Identity</span>
            </div>
            <div class="card-content">
                <div class="auth-types">
                    <div class="auth-type-item">
                        <span class="auth-type-name">Authentication:</span>
                        <span class="auth-type-desc">System verifies "Are you who you claim to be?" - Login, credentials</span>
                    </div>
                    <div class="auth-type-item">
                        <span class="auth-type-name">Authorization:</span>
                        <span class="auth-type-desc">System verifies "What are you allowed to do?" - Permissions, roles</span>
                    </div>
                </div>

                <div class="example-box">
                    <strong>💡 Real Example - Banking System:</strong>
                    <div class="auth-example">
                        <table class="mini-table">
                            <tr>
                                <td><strong>User Role</strong></td>
                                <td><strong>Features Accessible</strong></td>
                            </tr>
                            <tr>
                                <td>Admin</td>
                                <td>✓ All features + Reports + User Management</td>
                            </tr>
                            <tr>
                                <td>Premium Customer</td>
                                <td>✓ All standard features + Priority support</td>
                            </tr>
                            <tr>
                                <td>Free Customer</td>
                                <td>✓ Basic features only</td>
                            </tr>
                            <tr>
                                <td>Non-logged User</td>
                                <td>❌ Login page only</td>
                            </tr>
                        </table>
                    </div>
                </div>

                <div class="key-points">
                    <strong>🔍 Testing Checklist:</strong>
                    <ul>
                        <li>Valid credentials → Login succeeds</li>
                        <li>Invalid credentials → Login fails</li>
                        <li>Session timeout → Auto logout</li>
                        <li>User roles → Proper permission enforcement</li>
                        <li>Admin access → Prevent non-admin access</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 10. GUI TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #00BCD4 0%, #0097A7 100%);">
                <h4>🎨 GUI Testing</h4>
                <span class="badge visual">Visual Design</span>
                <span class="badge layout">Layout</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Checking if the UI is professionally designed and pixel-perfect</p>

                <div class="gui-checks">
                    <strong>🔍 GUI Testing Checklist:</strong>
                    <div class="check-item">
                        ✓ Alignment of objects (buttons, fields, images)
                    </div>
                    <div class="check-item">
                        ✓ Font sizes, styles, and colors consistent
                    </div>
                    <div class="check-item">
                        ✓ No broken frames or scattered content
                    </div>
                    <div class="check-item">
                        ✓ No object overlapping issues
                    </div>
                    <div class="check-item">
                        ✓ Professional color scheme
                    </div>
                    <div class="check-item">
                        ✓ Responsive design works on all screens
                    </div>
                    <div class="check-item">
                        ✓ Icons are clear and recognizable
                    </div>
                    <div class="check-item">
                        ✓ Text readability with proper contrast
                    </div>
                </div>
            </div>
        </div>

        <!-- 11. ACCESSIBILITY TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #66BB6A 0%, #43A047 100%);">
                <h4>♿ Accessibility Testing</h4>
                <span class="badge inclusive">Inclusive Design</span>
                <span class="badge wcag">WCAG</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Ensuring people with disabilities can use the application</p>

                <div class="accessibility-for">
                    <strong>👥 Testing For Different Disabilities:</strong>
                    
                    <div class="disability-item">
                        <span class="disability-icon">👨‍🦯</span>
                        <span><strong>Blind Users:</strong> Screen readers, keyboard navigation</span>
                    </div>
                    <div class="disability-item">
                        <span class="disability-icon">👂</span>
                        <span><strong>Deaf Users:</strong> Captions, subtitles, visual indicators</span>
                    </div>
                    <div class="disability-item">
                        <span class="disability-icon">♿</span>
                        <span><strong>Motor Disability:</strong> Keyboard navigation, large buttons</span>
                    </div>
                    <div class="disability-item">
                        <span class="disability-icon">🔍</span>
                        <span><strong>Color Blind:</strong> High contrast, not relying on color alone</span>
                    </div>
                    <div class="disability-item">
                        <span class="disability-icon">🧠</span>
                        <span><strong>Cognitive:</strong> Clear language, simple navigation</span>
                    </div>
                </div>

                <div class="standards-box">
                    <strong>📋 Standards to Follow:</strong>
                    <p>WCAG 2.1 (Web Content Accessibility Guidelines)</p>
                    <ul>
                        <li>Level A (Minimum)</li>
                        <li>Level AA (Enhanced)</li>
                        <li>Level AAA (Superior)</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- 12. GLOBALIZATION TESTING -->
        <div class="testing-type-card">
            <div class="card-header" style="background: linear-gradient(135deg, #FF6F00 0%, #E65100 100%);">
                <h4>🌍 Globalization Testing</h4>
                <span class="badge international">Multi-Language</span>
                <span class="badge localization">L10N/I18N</span>
            </div>
            <div class="card-content">
                <p><strong>What:</strong> Application works correctly for different languages and regions</p>

                <div class="i18n-l10n-box">
                    <div class="i18n-section">
                        <strong>🌐 I18N (Internationalization):</strong>
                        <p>Making software CAPABLE of supporting multiple languages</p>
                        <ul>
                            <li>Use property files for each language</li>
                            <li>Translate all text</li>
                            <li>Support right-to-left (Arabic, Hebrew)</li>
                        </ul>
                    </div>

                    <div class="l10n-section">
                        <strong>🗺️ L10N (Localization):</strong>
                        <p>Adapting software for SPECIFIC region/language</p>
                        <ul>
                            <li><strong>Date Format:</strong> US = MM/DD/YYYY, EU = DD/MM/YYYY, JP = YYYY/MM/DD</li>
                            <li><strong>Currency:</strong> $ (USD), Rs (INR), € (EUR), ¥ (JPY)</li>
                            <li><strong>Time Format:</strong> 12-hour vs 24-hour</li>
                            <li><strong>Numbers:</strong> 1,000.50 vs 1.000,50</li>
                            <li><strong>Timezone:</strong> EST, IST, JST, GMT</li>
                            <li><strong>Cultural Aspects:</strong> Colors, symbols, festivals</li>
                        </ul>
                    </div>
                </div>

                <div class="example-box">
                    <strong>💡 Example - Amazon Website for 10 Countries:</strong>
                    <div style="background: #f5f5f5; padding: 1rem; border-radius: 5px; margin: 0.5rem 0;">
                        <p><strong>Needs:</strong></p>
                        <ul>
                            <li>10+ language translation files</li>
                            <li>Region-specific pricing in local currencies</li>
                            <li>Shipping options per country</li>
                            <li>Payment methods available in that region</li>
                            <li>Tax calculation per country</li>
                            <li>Legal disclaimers in local language</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ADVANCED SECTION -->
    <section class="advanced-testing-section">
        <h3>🚀 Advanced Testing Concepts</h3>

        <!-- Testing Pyramid -->
        <div class="advanced-card">
            <h4>📊 Testing Pyramid Strategy</h4>
            <p>Optimal distribution of testing types for maximum ROI:</p>
            
            <div class="pyramid">
                <div class="pyramid-level pyramid-top">
                    <span class="level-name">E2E Tests</span>
                    <span class="level-percent">10%</span>
                    <span class="level-detail">Slow, expensive, comprehensive</span>
                </div>
                <div class="pyramid-level pyramid-middle">
                    <span class="level-name">Integration Tests</span>
                    <span class="level-percent">30%</span>
                    <span class="level-detail">Medium speed, moderate cost</span>
                </div>
                <div class="pyramid-level pyramid-bottom">
                    <span class="level-name">Unit Tests</span>
                    <span class="level-percent">60%</span>
                    <span class="level-detail">Fast, cheap, focused</span>
                </div>
            </div>

            <div class="key-points">
                <strong>💡 Key Insight:</strong>
                <p>Invest MORE in unit tests (fast feedback, cheap to fix). Less on E2E tests (slow, expensive). This maximizes ROI!</p>
            </div>
        </div>

        <!-- Risk-Based Testing -->
        <div class="advanced-card">
            <h4>⚠️ Risk-Based Testing Approach</h4>
            <p>Allocate testing effort based on risk priority:</p>

            <div class="risk-matrix">
                <div class="risk-cell high-risk">
                    <span class="risk-level">HIGH RISK</span>
                    <span class="risk-features">Payment, Login, Money Transfer, Critical Data</span>
                    <span class="effort">80% Testing Effort</span>
                </div>
                <div class="risk-cell medium-risk">
                    <span class="risk-level">MEDIUM RISK</span>
                    <span class="risk-features">Reporting, Search, Profile Settings</span>
                    <span class="effort">15% Testing Effort</span>
                </div>
                <div class="risk-cell low-risk">
                    <span class="risk-level">LOW RISK</span>
                    <span class="risk-features">Help Page, About Us, UI Elements</span>
                    <span class="effort">5% Testing Effort</span>
                </div>
            </div>
        </div>

        <!-- Test Metrics -->
        <div class="advanced-card">
            <h4>📈 Critical Test Metrics</h4>
            
            <div class="metrics-detailed">
                <div class="metric-box">
                    <strong>1. Test Coverage</strong>
                    <p>% of features/code tested</p>
                    <p class="formula">Target: >80%</p>
                </div>
                <div class="metric-box">
                    <strong>2. Defect Density</strong>
                    <p>Defects per 1000 lines of code (KLOC)</p>
                    <p class="formula">Target: <1 defect/KLOC</p>
                </div>
                <div class="metric-box">
                    <strong>3. Defect Removal Efficiency</strong>
                    <p>Defects found before release / Total defects</p>
                    <p class="formula">Target: >90%</p>
                </div>
                <div class="metric-box">
                    <strong>4. Test Effectiveness</strong>
                    <p>Defects found by testers / Total defects in system</p>
                    <p class="formula">Target: >85%</p>
                </div>
            </div>
        </div>

        <!-- Cost of Defects -->
        <div class="advanced-card">
            <h4>💰 Cost of Defects Across SDLC</h4>
            
            <div class="cost-analysis">
                <div class="cost-phase-item">
                    <span class="phase">Requirements</span>
                    <span class="cost">$1</span>
                    <span class="multiplier">1x</span>
                </div>
                <div class="cost-arrow">↓ 10x</div>

                <div class="cost-phase-item">
                    <span class="phase">Design</span>
                    <span class="cost">$10</span>
                    <span class="multiplier">1x</span>
                </div>
                <div class="cost-arrow">↓ 5x</div>

                <div class="cost-phase-item">
                    <span class="phase">Development</span>
                    <span class="cost">$50</span>
                    <span class="multiplier">1x</span>
                </div>
                <div class="cost-arrow">↓ 2x</div>

                <div class="cost-phase-item">
                    <span class="phase">Testing</span>
                    <span class="cost">$100</span>
                    <span class="multiplier">1x</span>
                </div>
                <div class="cost-arrow">↓ 10x</div>

                <div class="cost-phase-item final">
                    <span class="phase">Production 🔴</span>
                    <span class="cost">$1000+</span>
                    <span class="multiplier">10x</span>
                </div>
            </div>

            <div class="conclusion-box">
                <strong>💡 Key Takeaway:</strong>
                <p>A defect found in requirements phase costs $1 to fix.</p>
                <p style="color: red; font-weight: bold;">The SAME defect in production costs $1000+ to fix!</p>
                <p style="margin-top: 1rem;"><strong>➜ Testing is not a cost, it's an INVESTMENT that saves 1000x!</strong></p>
            </div>
        </div>
    </section>

    <!-- DECISION MATRIX -->
    <section class="decision-matrix-section">
        <h3>🎯 When to Use Which Testing Type?</h3>
        
        <table class="decision-table">
            <thead>
                <tr>
                    <th width="20%">Situation</th>
                    <th width="25%">Use This Type</th>
                    <th width="35%">Why?</th>
                    <th width="20%">Timeline</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>✅ New build received</td>
                    <td><strong>Smoke Testing</strong></td>
                    <td>Quick check - save weeks if broken</td>
                    <td>30 min - 2 hrs</td>
                </tr>
                <tr>
                    <td>🔧 Bug fix received</td>
                    <td><strong>Retesting + Regression</strong></td>
                    <td>Verify fix and nothing else broke</td>
                    <td>1-2 days</td>
                </tr>
                <tr>
                    <td>🌍 Multi-country app</td>
                    <td><strong>Globalization Testing</strong></td>
                    <td>Different languages and formats needed</td>
                    <td>2-4 weeks</td>
                </tr>
                <tr>
                    <td>📱 Mobile app</td>
                    <td><strong>Compatibility + Performance</strong></td>
                    <td>Different devices and network speeds</td>
                    <td>2-3 weeks</td>
                </tr>
                <tr>
                    <td>🏦 Banking app</td>
                    <td><strong>Security + Reliability</strong></td>
                    <td>Critical for money and data safety</td>
                    <td>4-6 weeks</td>
                </tr>
                <tr>
                    <td>⚡ Slow website</td>
                    <td><strong>Performance + Load Testing</strong></td>
                    <td>Find bottlenecks and capacity limits</td>
                    <td>1-2 weeks</td>
                </tr>
                <tr>
                    <td>📊 Black Friday Sale</td>
                    <td><strong>Load + Stress Testing</strong></td>
                    <td>Prepare for 100x normal traffic</td>
                    <td>3-4 weeks</td>
                </tr>
                <tr>
                    <td>🚀 Before go-live</td>
                    <td><strong>ALL types (comprehensive)</strong></td>
                    <td>Ensure production-ready quality</td>
                    <td>6-8 weeks</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- KEY STATISTICS -->
    <section class="stats-section">
        <h3>📊 Real-World Testing Statistics & Market Data</h3>
        
        <div class="big-stats">
            <div class="big-stat">
                <div class="stat-value">80%</div>
                <div class="stat-label">Of project time spent on Test Execution</div>
            </div>
            <div class="big-stat">
                <div class="stat-value">20%</div>
                <div class="stat-label">On Planning, Design & Review</div>
            </div>
            <div class="big-stat">
                <div class="stat-value">50%</div>
                <div class="stat-label">Cost increase per defect phase jump</div>
            </div>
            <div class="big-stat">
                <div class="stat-value">10x</div>
                <div class="stat-label">Higher cost to fix in production vs dev</div>
            </div>
            <div class="big-stat">
                <div class="stat-value">Zero</div>
                <div class="stat-label">Defect-free software products exist</div>
            </div>
            <div class="big-stat">
                <div class="stat-value">100%</div>
                <div class="stat-label">Testing is important for quality</div>
            </div>
        </div>
    </section>

    <!-- KEY TAKEAWAYS -->
    <section class="takeaways-section">
        <h3>🎓 Key Takeaways - Master These!</h3>
        
        <div class="takeaway-list">
            <div class="takeaway">
                <span class="number">1</span>
                <span class="text"><strong>Know All 27+ Types:</strong> Master when and how to use each testing type based on context</span>
            </div>
            <div class="takeaway">
                <span class="number">2</span>
                <span class="text"><strong>Functional + Non-Functional:</strong> Use BOTH together for complete quality assurance</span>
            </div>
            <div class="takeaway">
                <span class="number">3</span>
                <span class="text"><strong>Early Testing Saves $$:</strong> Find bugs in requirements phase = 100-1000x cheaper than production</span>
            </div>
            <div class="takeaway">
                <span class="number">4</span>
                <span class="text"><strong>Regression is Non-Negotiable:</strong> Every code change needs regression testing</span>
            </div>
            <div class="takeaway">
                <span class="number">5</span>
                <span class="text"><strong>Risk-Based Priority:</strong> Focus testing on critical features and high-risk areas first</span>
            </div>
            <div class="takeaway">
                <span class="number">6</span>
                <span class="text"><strong>Document Everything:</strong> Test cases enable consistency, reusability, and knowledge transfer</span>
            </div>
            <div class="takeaway">
                <span class="number">7</span>
                <span class="text"><strong>Automate Wisely:</strong> Manual for new features, automate for regression and repetitive tests</span>
            </div>
            <div class="takeaway">
                <span class="number">8</span>
                <span class="text"><strong>Think Like Users:</strong> Ad-hoc and exploratory testing catch real-world bugs automation misses</span>
            </div>
        </div>
    </section>

    <!-- STYLING -->
    <style>
        /* Testing Types Page Specific Styles */
        .tab-header {
            text-align: center;
            margin-bottom: 2rem;
            border-bottom: 3px solid var(--primary);
            padding-bottom: 1rem;
        }

        .tab-header h2 {
            color: var(--primary);
            font-size: 2em;
            margin-bottom: 0.5rem;
        }

        .subtitle {
            color: #666;
            font-size: 1.05em;
            font-style: italic;
        }

        /* Statistics Container */
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
            margin: 2rem 0;
            padding: 1rem;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            border-radius: 10px;
        }

        .stat-box {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            border-top: 4px solid var(--primary);
        }

        .stat-number {
            font-size: 1.8em;
            font-weight: bold;
            color: var(--primary);
            display: block;
            margin-bottom: 0.5rem;
        }

        .stat-label {
            font-size: 0.9em;
            color: #666;
        }

        /* Classification Grid */
        .classification-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin: 2rem 0;
        }

        .classification-card {
            background: white;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            border-top: 5px solid;
            transition: all 0.3s;
        }

        .classification-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.15);
        }

        .classification-card.functional {
            border-top-color: #2196F3;
        }

        .classification-card.non-functional {
            border-top-color: #FF9800;
        }

        .card-icon {
            font-size: 3em;
            margin-bottom: 1rem;
        }

        .card-icon {
            font-size: 3em;
            margin-bottom: 1rem;
        }

        .classification-card h4 {
            color: var(--primary);
            margin-bottom: 0.5rem;
            font-size: 1.3em;
        }

        .card-subtitle {
            color: #666;
            margin-bottom: 1rem;
            font-style: italic;
        }

        .features-list {
            list-style: none;
            margin: 1rem 0;
        }

        .features-list li {
            padding: 0.5rem 0;
            color: #555;
        }

        .card-stat {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
            padding: 0.8rem;
            border-radius: 5px;
            margin-top: 1rem;
            text-align: center;
            font-weight: bold;
        }

        /* Testing Types Section */
        .testing-types-section {
            margin: 3rem 0;
        }

        .testing-types-section > h3 {
            color: var(--primary);
            font-size: 1.6em;
            margin-bottom: 1.5rem;
            padding-bottom: 0.8rem;
            border-bottom: 3px solid var(--primary);
        }

        /* Testing Type Card */
        .testing-type-card {
            background: white;
            border-radius: 10px;
            margin-bottom: 1.5rem;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            overflow: hidden;
            border-left: 5px solid var(--primary);
            transition: all 0.3s;
        }

        .testing-type-card:hover {
            box-shadow: 0 8px 20px rgba(0,0,0,0.15);
            transform: translateX(5px);
        }

        .testing-type-card.highlight-critical {
            border-left: 5px solid #FF9800;
        }

        .testing-type-card.highlight-star {
            border-left: 5px solid #FFD700;
        }

        .card-header {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
            padding: 1.5rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .card-header h4 {
            color: white;
            margin: 0;
            font-size: 1.2em;
            flex: 1;
            min-width: 250px;
        }

        .badge {
            background: rgba(255,255,255,0.3);
            padding: 0.4rem 0.8rem;
            border-radius: 20px;
            font-size: 0.85em;
            font-weight: 500;
            white-space: nowrap;
        }

        .badge.developer { background: rgba(100,200,255,0.6); }
        .badge.whitebox { background: rgba(150,150,255,0.6); }
        .badge.both { background: rgba(100,255,100,0.6); }
        .badge.graybox { background: rgba(200,200,100,0.6); }
        .badge.qa { background: rgba(255,150,100,0.6); }
        .badge.blackbox { background: rgba(200,100,100,0.6); }
        .badge.business { background: rgba(255,200,100,0.6); }
        .badge.urgent { background: rgba(255,100,100,0.8); }
        .badge.quick { background: rgba(100,255,100,0.8); }
        .badge.compare { background: rgba(150,200,255,0.6); }
        .badge.workflow { background: rgba(200,100,255,0.6); }
        .badge.integration { background: rgba(100,200,200,0.6); }
        .badge.critical { background: rgba(255,100,100,0.8); }
        .badge.repeated { background: rgba(255,200,100,0.8); }
        .badge.random { background: rgba(100,200,255,0.6); }
        .badge.experience { background: rgba(200,150,255,0.6); }
        .badge.unscripted { background: rgba(150,200,100,0.6); }
        .badge.learning { background: rgba(200,200,100,0.6); }
        .badge.quality { background: rgba(100,255,200,0.6); }
        .badge.deep { background: rgba(255,150,150,0.6); }
        .badge.speed { background: rgba(255,100,100,0.6); }
        .badge.efficiency { background: rgba(100,255,100,0.6); }
        .badge.heavy { background: rgba(100,200,255,0.6); }
        .badge.capacity { background: rgba(200,100,255,0.6); }
        .badge.breaking { background: rgba(255,100,100,0.8); }
        .badge.extreme { background: rgba(255,150,100,0.8); }
        .badge.ux { background: rgba(100,200,255,0.6); }
        .badge.ui { background: rgba(200,150,255,0.6); }
        .badge.cross { background: rgba(100,255,200,0.6); }
        .badge.environments { background: rgba(200,200,100,0.6); }
        .badge.protection { background: rgba(255,100,100,0.6); }
        .badge.continuous { background: rgba(100,255,100,0.6); }
        .badge.stability { background: rgba(200,200,255,0.6); }
        .badge.disaster { background: rgba(255,150,100,0.6); }
        .badge.resilience { background: rgba(100,200,100,0.6); }
        .badge.access { background: rgba(100,200,255,0.6); }
        .badge.identity { background: rgba(200,100,200,0.6); }
        .badge.visual { background: rgba(100,255,255,0.6); }
        .badge.layout { background: rgba(200,150,255,0.6); }
        .badge.inclusive { background: rgba(100,255,100,0.6); }
        .badge.wcag { background: rgba(200,200,100,0.6); }
        .badge.international { background: rgba(255,150,100,0.6); }
        .badge.localization { background: rgba(100,200,255,0.6); }

        .card-content {
            padding: 1.5rem;
        }

        .content-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin-bottom: 1.5rem;
        }

        .content-item {
            background: #f5f7fa;
            padding: 1rem;
            border-radius: 5px;
            font-size: 0.95em;
        }

        .content-item strong {
            color: var(--primary);
            display: block;
            margin-bottom: 0.3rem;
        }

        /* Example Box */
        .example-box {
            background: #e3f2fd;
            border-left: 4px solid #2196F3;
            padding: 1rem;
            margin: 1rem 0;
            border-radius: 5px;
            color: #1565c0;
        }

        .example-box strong {
            display: block;
            margin-bottom: 0.5rem;
            color: #1565c0;
        }

        .example-content {
            margin-left: 1rem;
        }

        .example-content ul {
            margin: 0.5rem 0 0 1.5rem;
        }

        /* Flow Diagram */
        .flow-diagram {
            display: flex;
            align-items: center;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin: 1.5rem 0;
            padding: 1rem;
            background: #f9f9f9;
            border-radius: 5px;
        }

        .flow-step {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
            padding: 0.8rem 1rem;
            border-radius: 5px;
            font-weight: 500;
            text-align: center;
            min-width: 120px;
        }

        .flow-arrow, .workflow-arrow, .cost-arrow {
            color: var(--primary);
            font-weight: bold;
            font-size: 1.2em;
        }

        /* Workflow Chain */
        .workflow-chain {
            display: flex;
            align-items: center;
            justify-content: center;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin: 1rem 0;
            padding: 1rem;
            background: #f5f5f5;
            border-radius: 5px;
        }

        .workflow-item {
            background: #667eea;
            color: white;
            padding: 0.8rem 1.2rem;
            border-radius: 5px;
            font-weight: 500;
        }

        /* Key Points */
        .key-points {
            background: #f5f5f5;
            padding: 1rem;
            border-left: 4px solid var(--primary);
            border-radius: 5px;
            margin: 1rem 0;
        }

        .key-points strong {
            display: block;
            margin-bottom: 0.5rem;
            color: var(--primary);
        }

        .key-points ul {
            margin: 0.5rem 0 0 1.5rem;
        }

        /* Approaches Box */
        .approaches-box {
            margin: 1rem 0;
        }

        .approaches-box strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .approach-item {
            background: #f5f5f5;
            padding: 0.8rem;
            margin-bottom: 0.5rem;
            border-left: 4px solid #2196F3;
            border-radius: 5px;
        }

        .approach-name {
            font-weight: bold;
            color: var(--primary);
            display: block;
            margin-bottom: 0.3rem;
        }

        /* Alert Box */
        .alert-box {
            padding: 1rem;
            margin: 1rem 0;
            border-left: 4px solid;
            border-radius: 5px;
        }

        .alert-box.info {
            background: #e3f2fd;
            border-left-color: #2196F3;
            color: #1565c0;
        }

        .alert-box.warning {
            background: #fff3e0;
            border-left-color: #FF9800;
            color: #e65100;
        }

        .alert-box.danger {
            background: #ffebee;
            border-left-color: #f44336;
            color: #c62828;
        }

        .alert-box.success {
            background: #e8f5e9;
            border-left-color: #4CAF50;
            color: #2e7d32;
        }

        .alert-box strong {
            display: block;
            margin-bottom: 0.5rem;
        }

        .highlight-red {
            color: red;
        }

        /* Benefit Box */
        .benefit-box {
            background: #e8f5e9;
            border-left: 4px solid #4CAF50;
            padding: 1rem;
            margin: 1rem 0;
            border-radius: 5px;
            color: #2e7d32;
        }

        .benefit-box strong {
            display: block;
            margin-bottom: 0.5rem;
        }

        /* Solution Box */
        .solution-box {
            background: #e8f5e9;
            border-left: 4px solid #4CAF50;
            padding: 1rem;
            margin: 1rem 0;
            border-radius: 5px;
            color: #2e7d32;
        }

        /* Comparison Table */
        .comparison-table {
            width: 100%;
            margin: 1rem 0;
            border-collapse: collapse;
            background: white;
        }

        .comparison-table tr {
            border-bottom: 1px solid #ddd;
        }

        .comparison-table td {
            padding: 0.8rem;
            text-align: left;
        }

        .comparison-table tr:hover {
            background: #f5f5f5;
        }

        .compare-table {
            width: 100%;
            border-collapse: collapse;
            background: white;
            margin: 1rem 0;
        }

        .compare-table tr {
            border-bottom: 1px solid #ddd;
        }

        .compare-table td {
            padding: 0.8rem;
        }

        .compare-table tr:hover {
            background: #f5f5f5;
        }

        .compare-table tr:first-child {
            background: #f5f5f5;
            font-weight: bold;
        }

        .comparison-table-full {
            width: 100%;
            border-collapse: collapse;
            margin: 1.5rem 0;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .comparison-table-full th {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
            padding: 1rem;
            text-align: left;
            font-weight: 600;
        }

        .comparison-table-full td {
            padding: 0.8rem 1rem;
            border-bottom: 1px solid #ddd;
        }

        .comparison-table-full tr:hover {
            background: #f5f5f5;
        }

        /* Mini Table */
        .mini-table {
            width: 100%;
            border-collapse: collapse;
            background: white;
            margin: 0.5rem 0;
        }

        .mini-table tr {
            border-bottom: 1px solid #ddd;
        }

        .mini-table td {
            padding: 0.6rem;
            font-size: 0.95em;
        }

        .mini-table tr:first-child {
            background: #f5f5f5;
            font-weight: bold;
        }

        /* Variants Box */
        .uat-variants, .variant-item, .reg-type-item {
            margin: 1rem 0;
        }

        .variant-item {
            background: #f5f5f5;
            padding: 1rem;
            border-left: 4px solid #2196F3;
            border-radius: 5px;
            margin-bottom: 0.5rem;
        }

        .variant-item strong {
            color: var(--primary);
            display: block;
            margin-bottom: 0.3rem;
        }

        /* Regression Types */
        .regression-types-box {
            margin: 1rem 0;
        }

        .regression-types-box strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .reg-type-item {
            background: white;
            border: 2px solid #f0f0f0;
            padding: 1rem;
            margin-bottom: 1rem;
            border-radius: 5px;
            border-left: 4px solid var(--primary);
        }

        .reg-type-header {
            font-weight: bold;
            color: var(--primary);
            display: block;
            margin-bottom: 0.5rem;
        }

        .reg-type-content {
            font-size: 0.95em;
            color: #555;
        }

        .reg-type-content strong {
            color: var(--primary);
        }

        .reg-type-content p {
            margin: 0.3rem 0;
            font-size: 0.9em;
        }

        /* Critical Checks */
        .critical-checks {
            margin: 1rem 0;
        }

        .critical-checks strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .check-item {
            background: #e8f5e9;
            padding: 0.8rem;
            margin-bottom: 0.5rem;
            border-radius: 5px;
            border-left: 4px solid #4CAF50;
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .check-icon {
            color: #4CAF50;
            font-weight: bold;
            font-size: 1.2em;
        }

        /* Metrics Box */
        .metrics-box {
            margin: 1rem 0;
        }

        .metrics-box strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .metric-item {
            background: #f5f5f5;
            padding: 0.8rem;
            margin-bottom: 0.5rem;
            border-left: 4px solid #2196F3;
            border-radius: 5px;
            display: flex;
            gap: 1rem;
        }

        .metric-name {
            font-weight: bold;
            color: var(--primary);
            min-width: 150px;
        }

        .metric-value {
            color: #555;
        }

        /* Tools Box */
        .tools-box {
            background: #f5f5f5;
            padding: 1rem;
            border-left: 4px solid var(--primary);
            border-radius: 5px;
            margin: 1rem 0;
        }

        .tools-box strong {
            color: var(--primary);
        }

        /* Performance Chart */
        .performance-chart {
            margin: 1rem 0;
        }

        .performance-chart strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        /* Stress Scenarios */
        .stress-scenarios {
            margin: 1rem 0;
        }

        .stress-scenarios strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .scenario-item {
            background: #ffebee;
            padding: 0.8rem;
            margin-bottom: 0.5rem;
            border-left: 4px solid #f44336;
            border-radius: 5px;
            color: #c62828;
        }

        /* Expectation Box */
        .expectation-box {
            background: #e8f5e9;
            border-left: 4px solid #4CAF50;
            padding: 1rem;
            margin: 1rem 0;
            border-radius: 5px;
            color: #2e7d32;
        }

        .expectation-box strong {
            display: block;
            margin-bottom: 1rem;
        }

        .expectation-box ul {
            margin-left: 1.5rem;
        }

        /* Usability Questions */
        .usability-questions {
            margin: 1rem 0;
        }

        .usability-questions strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .usability-questions ul {
            margin-left: 1.5rem;
        }

        .usability-questions li {
            margin-bottom: 0.5rem;
            color: #555;
        }

        /* Compatibility Matrix */
        .compat-matrix {
            margin: 1rem 0;
        }

        .compat-matrix strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .compat-category {
            background: #f5f5f5;
            padding: 0.8rem;
            margin-bottom: 0.5rem;
            border-left: 4px solid #2196F3;
            border-radius: 5px;
        }

        .compat-category strong {
            color: var(--primary);
            display: block;
            margin-bottom: 0.3rem;
        }

        .compat-category span {
            display: block;
            color: #555;
            font-size: 0.95em;
        }

        /* Security Tests */
        .security-tests {
            margin: 1rem 0;
        }

        .security-tests strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .sec-test-item {
            background: #f5f5f5;
            padding: 0.8rem;
            margin-bottom: 0.5rem;
            border-left: 4px solid #f44336;
            border-radius: 5px;
        }

        .sec-test-name {
            font-weight: bold;
            color: #f44336;
        }

        .sec-test-desc {
            color: #555;
            font-size: 0.95em;
        }

        /* Reliability Metrics */
        .reliability-metrics {
            margin: 1rem 0;
        }

        .reliability-metrics strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        /* Recovery Scenarios */
        .recovery-scenarios {
            margin: 1rem 0;
        }

        .recovery-scenarios strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .scenario-item {
            background: #fff3e0;
            padding: 0.8rem;
            margin-bottom: 0.5rem;
            border-left: 4px solid #FF9800;
            border-radius: 5px;
            color: #e65100;
        }

        /* Recovery Expected */
        .recovery-expected {
            background: #e8f5e9;
            border-left: 4px solid #4CAF50;
            padding: 1rem;
            margin: 1rem 0;
            border-radius: 5px;
            color: #2e7d32;
        }

        .recovery-expected ul {
            margin-left: 1.5rem;
        }

        /* Auth Types */
        .auth-types {
            margin: 1rem 0;
        }

        .auth-type-item {
            background: #f5f5f5;
            padding: 1rem;
            margin-bottom: 1rem;
            border-left: 4px solid #2196F3;
            border-radius: 5px;
        }

        .auth-type-name {
            font-weight: bold;
            color: var(--primary);
            display: block;
            margin-bottom: 0.5rem;
        }

        .auth-type-desc {
            color: #555;
        }

        /* Auth Example */
        .auth-example {
            margin: 1rem 0;
        }

        /* GUI Checks */
        .gui-checks {
            margin: 1rem 0;
        }

        .gui-checks strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .check-item {
            background: #e8f5e9;
            padding: 0.8rem;
            margin-bottom: 0.5rem;
            border-radius: 5px;
            border-left: 4px solid #4CAF50;
        }

        /* Accessibility For */
        .accessibility-for {
            margin: 1rem 0;
        }

        .accessibility-for strong {
            display: block;
            margin-bottom: 1rem;
            color: var(--primary);
        }

        .disability-item {
            background: #f5f5f5;
            padding: 0.8rem;
            margin-bottom: 0.5rem;
            border-left: 4px solid #4CAF50;
            border-radius: 5px;
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .disability-icon {
            font-size: 1.5em;
            min-width: 40px;
        }

        /* Standards Box */
        .standards-box {
            background: #f5f5f5;
            padding: 1rem;
            border-left: 4px solid var(--primary);
            border-radius: 5px;
            margin: 1rem 0;
        }

        /* I18N L10N Box */
        .i18n-l10n-box {
            margin: 1rem 0;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
        }

        .i18n-section, .l10n-section {
            background: #f5f5f5;
            padding: 1rem;
            border-radius: 5px;
            border-left: 4px solid #2196F3;
        }

        .i18n-section strong, .l10n-section strong {
            display: block;
            margin-bottom: 0.5rem;
            color: var(--primary);
        }

        .i18n-section ul, .l10n-section ul {
            margin-left: 1.5rem;
        }

        /* Advanced Section */
        .advanced-testing-section {
            margin-top: 3rem;
            padding: 2rem;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            border-radius: 10px;
        }

        .advanced-testing-section > h3 {
            color: var(--primary);
            font-size: 1.6em;
            margin-bottom: 1.5rem;
            padding-bottom: 0.8rem;
            border-bottom: 3px solid var(--primary);
        }

        /* Advanced Card */
        .advanced-card {
            background: white;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            border-left: 5px solid var(--primary);
        }

        .advanced-card h4 {
            color: var(--primary);
            margin-bottom: 1rem;
            font-size: 1.2em;
        }

        /* Pyramid */
        .pyramid {
            margin: 1.5rem 0;
        }

        .pyramid-level {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem;
            margin: 0.5rem auto;
            border-radius: 5px;
            color: white;
            font-weight: 600;
        }

        .pyramid-top {
            background: linear-gradient(90deg, var(--primary) 0%, var(--primary-dark) 100%);
            width: 25%;
        }

        .pyramid-middle {
            background: linear-gradient(90deg, var(--primary) 0%, var(--primary-dark) 100%);
            width: 60%;
        }

        .pyramid-bottom {
            background: linear-gradient(90deg, var(--primary) 0%, var(--primary-dark) 100%);
            width: 100%;
        }

        .level-name {
            font-weight: bold;
            min-width: 100px;
        }

        .level-percent {
            background: rgba(0,0,0,0.2);
            padding: 0.3rem 0.8rem;
            border-radius: 3px;
            font-size: 0.9em;
        }

        .level-detail {
            font-size: 0.85em;
            opacity: 0.9;
        }

        /* Risk Matrix */
        .risk-matrix {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin: 1rem 0;
        }

        .risk-cell {
            padding: 1.5rem;
            border-radius: 8px;
            color: white;
            display: flex;
            flex-direction: column;
            gap: 0.8rem;
        }

        .risk-cell.high-risk {
            background: linear-gradient(135deg, #FF6B6B 0%, #EE5A52 100%);
        }

        .risk-cell.medium-risk {
            background: linear-gradient(135deg, #FFA500 0%, #FF8C00 100%);
        }

        .risk-cell.low-risk {
            background: linear-gradient(135deg, #4CAF50 0%, #3D8B40 100%);
        }

        .risk-level {
            font-weight: bold;
            font-size: 1.1em;
        }

        .risk-features {
            font-size: 0.95em;
            opacity: 0.9;
        }

        .effort {
            background: rgba(0,0,0,0.2);
            padding: 0.5rem;
            border-radius: 3px;
            font-weight: bold;
            text-align: center;
        }

        /* Metrics Detailed */
        .metrics-detailed {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
            margin: 1rem 0;
        }

        .metric-box {
            background: white;
            padding: 1rem;
            border-radius: 8px;
            border-top: 4px solid var(--primary);
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .metric-box strong {
            display: block;
            color: var(--primary);
            margin-bottom: 0.5rem;
        }

        .metric-box p {
            color: #555;
            font-size: 0.95em;
            margin: 0.3rem 0;
        }

        .formula {
            background: #f5f5f5;
            padding: 0.5rem;
            border-radius: 3px;
            color: #c62828;
            font-weight: bold;
            margin-top: 0.5rem;
        }

        /* Cost Analysis */
        .cost-analysis {
            margin: 1rem 0;
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
        }

        .cost-phase-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem;
            background: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .cost-phase-item.final {
            background: linear-gradient(135deg, #ffcdd2 0%, #ef9a9a 100%);
            font-weight: bold;
        }

        .phase {
            font-weight: bold;
            color: var(--primary);
            min-width: 120px;
        }

        .cost {
            font-size: 1.3em;
            font-weight: bold;
            color: #c62828;
        }

        .multiplier {
            background: rgba(0,0,0,0.1);
            padding: 0.5rem 1rem;
            border-radius: 3px;
            font-weight: bold;
        }

        /* Conclusion Box */
        .conclusion-box {
            background: linear-gradient(135deg, #fff3e0 0%, #ffe0b2 100%);
            border-left: 4px solid #FF9800;
            padding: 1.5rem;
            margin: 1rem 0;
            border-radius: 5px;
            color: #e65100;
        }

        .conclusion-box strong {
            display: block;
            margin-bottom: 0.5rem;
        }

        /* Decision Matrix Section */
        .decision-matrix-section {
            margin-top: 3rem;
            padding: 2rem;
            background: white;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        .decision-matrix-section > h3 {
            color: var(--primary);
            font-size: 1.6em;
            margin-bottom: 1.5rem;
            padding-bottom: 0.8rem;
            border-bottom: 3px solid var(--primary);
        }

        .decision-table {
            width: 100%;
            border-collapse: collapse;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            margin-top: 1rem;
        }

        .decision-table th {
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
            padding: 1rem;
            text-align: left;
            font-weight: 600;
        }

        .decision-table td {
            padding: 1rem;
            border-bottom: 1px solid #ddd;
        }

        .decision-table tr:hover {
            background: #f5f5f5;
        }

        .decision-table td:first-child {
            font-weight: bold;
            color: var(--primary);
        }

        /* Stats Section */
        .stats-section {
            margin-top: 3rem;
            padding: 2rem;
            background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
            border-radius: 10px;
        }

        .stats-section > h3 {
            color: var(--primary);
            font-size: 1.6em;
            margin-bottom: 1.5rem;
            text-align: center;
            padding-bottom: 0.8rem;
            border-bottom: 3px solid var(--primary);
        }

        .big-stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }

        .big-stat {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
            transition: all 0.3s;
            border-top: 4px solid var(--primary);
        }

        .big-stat:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.15);
        }

        .stat-value {
            font-size: 2em;
            font-weight: bold;
            color: var(--primary);
            display: block;
            margin-bottom: 0.5rem;
        }

        .stat-label {
            font-size: 0.95em;
            color: #666;
        }

        /* Takeaways Section */
        .takeaways-section {
            margin-top: 3rem;
            padding: 2rem;
            background: #e8f5e9;
            border-radius: 10px;
            border: 2px solid #4CAF50;
        }

        .takeaways-section > h3 {
            color: #2e7d32;
            font-size: 1.6em;
            margin-bottom: 1.5rem;
            text-align: center;
            padding-bottom: 0.8rem;
            border-bottom: 3px solid #4CAF50;
        }

        .takeaway-list {
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }

        .takeaway {
            display: flex;
            gap: 1rem;
            align-items: flex-start;
            background: white;
            padding: 1rem;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .number {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-dark) 100%);
            color: white;
            border-radius: 50%;
            font-weight: bold;
            flex-shrink: 0;
        }

        .text {
            color: #333;
            font-size: 0.95em;
            line-height: 1.6;
        }

        .text strong {
            color: var(--primary);
        }

        /* Responsive */
        @media (max-width: 768px) {
            .classification-grid {
                grid-template-columns: 1fr;
            }

            .content-grid {
                grid-template-columns: 1fr;
            }

            .stats-container {
                grid-template-columns: repeat(2, 1fr);
            }

            .big-stats {
                grid-template-columns: repeat(2, 1fr);
            }

            .card-header {
                flex-direction: column;
                align-items: flex-start;
            }

            .card-header h4 {
                min-width: auto;
            }

            .flow-diagram {
                flex-direction: column;
            }

            .workflow-chain {
                flex-direction: column;
            }

            .compat-matrix, .i18n-l10n-box {
                grid-template-columns: 1fr;
            }

            .risk-matrix {
                grid-template-columns: 1fr;
            }

            .metrics-detailed {
                grid-template-columns: 1fr;
            }

            .cost-analysis {
                flex-direction: column;
            }

            .pyramid-top, .pyramid-middle, .pyramid-bottom {
                width: 100% !important;
            }

            .decision-table {
                font-size: 0.9em;
            }

            .decision-table th, .decision-table td {
                padding: 0.6rem;
            }
        }
    </style>
</div>