Download Link: https://assignmentchef.com/product/solved-cis301-homework-5-predicate-logic
<br>
Purpose of Assignment:

To help you understand …

<ol>

 <li>natural deduction rules for propositional logic</li>

 <li>how to apply the rules for proving validity of sequents</li>

 <li>some properties of propositional logic connectives and how they can be proven using natural deduction</li>

</ol>

We have created some automated grading tools to speed the grading of homeworks. To apply those tools, we need to make sure that each student uses a consistent naming for all their solutions file. Therefore, we have created an IntelliJ project with template files for your solution. DON’T CHANGE THE NAME OF ANY OF THE FILES that we give you.

<h1 id="hints">Hints:</h1>

If you get stuck in a proof, take a look at the tactics given in the lecture slides associated with the operators involved in the formulae.

Typically, you’ll introduce from the inside-out and eliminate from the outside-in

<h1 id="gettingstarted">Getting started</h1>

You can find examples of completed Logika propositional proofs in the Logika example repository (included in the class examples that you downloaded (as illustrated in the “Step #2” videos). Here is a direct link to the predicate logic proofs portion of those examples:https://github.com/sireum/v3-logika-examples/tree/release/src/predicate

<h1 id="considerations">Considerations</h1>

<ol>

 <li>All files must run in the Sireum IVE</li>

 <li>“Proof” means “a Logika 2 column proof”. And “Prove” means “provide a proof”</li>

 <li>To receive any points a problem must:</li>

</ol>

<ul>

 <li>be a Logika Propositional Proof</li>

 <li>contain the correct logical sequent</li>

</ul>

<ol>

 <li>Partial credit may be received if the proof is not finished.</li>

 <li>Correctly proven claims that do not progress the proof will not impact your grade</li>

 <li>Each provable sequent can be proven in at most 25 steps.</li>

 <li>Point values are proportional to difficulty.</li>

</ol>

<h1 id="usingpbc">Using PBC</h1>

Proof by contradiction, like any other rule, can be used to justify claims. Subproofs can be confusing or require additional work. Therefore, PBC should be avoided if possible. When trying to prove a claim, there is a simple test on whether PBC should be used to prove the claim. Only in these cases should PBC be used:

<ol>

 <li>The claim is just an atom i.e. p(x), or q</li>

 <li>The top level of the claim is or i.e. (p-&gt;q) V r</li>

 <li>The top level of the claim is the existential quantifier i.e. ∃ x p(x)</li>

</ol>

However sometimes, these can be justified without PBC. Sometimes these <em>can</em> be done directly. In any other case, there is a direct approach to build the claim using the previously justified claims.

<h1 id="problems">Problems</h1>

<ol>

 <li>(4 points) ∀ x ∀ y p(x, y) ⊢ ∀ y ∀ x p(x, y)</li>

 <li>(5 points) ∃ x ∃ y p(x, y) ⊢ ∃ y ∃ x p(x, y)</li>

 <li>(4 points) ¬(p → q) ⊢ p ∧ ¬q</li>

 <li>(5 points) ¬∃ x p(x) ⊢ ∀ x ¬p(x)If you have not read the above note on “Using PBC”, you should do so now.</li>

 <li>(6 points) ¬∀ x p(x) ⊢ ∃ x ¬p(x)</li>

 <li>(6 points) ¬∀ x p(x) → q(x) ⊢ ∃ x p(x) ∧ ¬q(x)</li>

</ol>