<template>
  <div>
    <section class="speciality-area">
      <div class="container">
        <div class="row justify-content-between">
          <h3>Ethics and Policies :</h3>
          <div class="ethicsContent">
            <p>
              International Journal of Scientific Research in Engineering &
              Technology (IJSREAT) is (Online), Bi-monthly international journal
              for publishing new ideas founded by academicians, educationists,
              engineers, and corporate people. The research results and
              fundamental advancement are all aspects of Innovative Research in
              Advanced Engineering & Technology, various engineering
              disciplines, etc. IJSREAT is a scholarly, open, accessible, Double
              Blind Peer Review Journal that helps an academic person and
              student community. International Journal of Scientific Research in
              Engineering & Technology provides the academic community and
              industry for submitting original research and applications related
              to Various Engineering disciplines and Advanced Technologies.
            </p>
            <p>
              Publishing an article in a Double-Blind Peer-Reviewed Journal is
              critical for developing a cohesive and acknowledged knowledge
              network. It immediately reflects the authors and the institutions
              that support them's work excellence. Articles that have been
              double-blind peer-reviewed support and represent the scientific
              process. As a result, it is critical to agree on required ethical
              conduct norms.
            </p>
          </div>
          <div class="ethicsContent">
            <h5>Ethics topics to consider when publishing:</h5>
            <p>
              <b>Authorship of the Paper:</b>Only individuals who made a
              significant effort to conceptualize, plan, carry out, or interpret
              the reported study should be allowed to sign their names as
              authors.
            </p>
            <p>
              <b>Originality and Plagiarism:</b>Authors should guarantee that
              they have authored original works and that if they have borrowed
              the work and words of others, they have appropriately cited or
              quoted them.
            </p>
            <p>
              <b>Data Access and Retention:</b>Authors may be required to
              provide the raw data related to a publication for editorial
              review; they should be ready to make the data available to the
              general public.
            </p>
            <p>
              <b>Multiple, redundant, or concurrent publishing:</b>An author
              should only publish submissions in one journal or principal
              publication that describe the same study. IJSREAT does not view
              the following uses of a work as prior publication:
            </p>
            <div>
              <ul>
                <li>
                  <p>Publication in the form of an abstract</p>
                </li>
                <li>
                  <p>Publication as an academic thesis</p>
                </li>
                <li>
                  <p>Publication as an electronic preprint</p>
                </li>
              </ul>
              <p>
                Information on prior international journal publications is included within IJSREAT journal Guide for Authors. 
              </p>
            </div>
            <p><b>Acknowledgment Of Sources:</b>Proper acknowledgment.</p>
            <p>
              <b>Disclosure and Any Conflicts of Interest:</b> Each submission
              must disclose any connections that might create a conflict of
              interest.
            </p>
            <p>
              <b>Fundamental Mistakes in Published Works: </b>When an author
              finds a substantial error or inaccuracy in their published work,
              they must contact the publisher or journal editor as soon as
              possible and work with the editor to withdraw or fix the
              publication.
            </p>
            <p>
              <b>Reporting Guidelines:</b> Writers of reports on original
              research should give a truthful assessment of the work done and an
              unbiased analysis of its relevance.
            </p>
            <p>
              <b>Hazards And Human or Animal Subjects:</b>Statements of
              compliance are necessary if the job contains substances, methods,
              or equipment that have particular dangers inherent in their usage
              or if the animal or human subjects are used.
            </p>
            <p>
              <b>Usage of Patient Photographs or Case Information: </b>Research
              involving patients or volunteers must get informed permission from
              all participants and be approved by an ethics committee. This
              approval must be included in the report.
            </p>
          </div>
          <div class="ethicsContent">
            <h5>Ethics and policy of IJSREAT are given below:</h5>
          </div>
        </div>

        <InstructionPolicyVue />
        <EthicsPolicyVue />
        <Withdrawal />
        <PeerReviewPolicyVue />
        <Plagiarism />
        <CopyrightPolicyVue />
        <LicensePolicy />
      </div>
    </section>
  </div>
</template>

<script>
import InstructionPolicyVue from "./Policies/InstructionPolicy.vue";
import EthicsPolicyVue from "./Policies/EthicsPolicy.vue";
import Withdrawal from "./Policies/Withdrawal.vue";
import PeerReviewPolicyVue from "./Policies/PeerReviewPolicy.vue";
import Plagiarism from "./Policies/PlagiarismPolicy.vue";
import CopyrightPolicyVue from "./Policies/CopyrightPolicy.vue";
import LicensePolicy from "./Policies/LicensePolicy.vue";
// import PrivacyPolicy from "./PrivacyPolicy.vue";
// import RefundPolicy from "./RefundPolicy.vue";

export default {
  name: "CompanyDescription",
  components: {
    InstructionPolicyVue,
    EthicsPolicyVue,
    Withdrawal,
    PeerReviewPolicyVue,
    Plagiarism,
    CopyrightPolicyVue,
    LicensePolicy,
    // PrivacyPolicy,
    // RefundPolicy,
  },
  data() {
    return {};
  },
};
</script>

<style scoped>
h5 {
  font-family: "Rubik", sans-serif;
  padding-bottom: 10px;
  font-size: 18px;
}
p {
  font-size: 16px;
  font-family: "Rubik", sans-serif;
  color: rgb(100, 117, 137);
  text-align: justify;
  text-justify: inter-word;
}
h3 {
  font-family: "Rubik", sans-serif;
  font-size: 24px;
}
.ethicsContent {
  padding-bottom: 10px;
}
</style>