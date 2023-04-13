# Principle of Least Privilege (PoLP)

<aside>
⚠️ Provide the user, role or application the l**east amount of permissions to perform an action**

</aside>

**Just-Enough-Access (JEA)** - permitting only the exact actions

**Just-In-Time (JIT)** - Permitting the smallest duration an identity can use permissions

**Risk-based adaptive policies**

Each attempt to access a resource generates a risk score of how likely it is to be coming from a compromised source.

Device + location + IP + MFA? etc

**AWS does not implement Risk-based adaptive policies**

Have to rely on third-party identity solutions

# ConsoleMe

![Untitled](Principle%20of%20Least%20Privilege%20(PoLP)%203ec190c1c4b8440abf9c1e169e802131/Untitled.png)

“I want these things” > “Ok, you can have them” or “You don’t need them”